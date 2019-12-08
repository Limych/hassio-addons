#
# Multi stage build of add-on container
#

ARG BUILD_FROM=debian:stretch-slim

# Build arguments
#ARG BUILD_ARCH

# STAGE 2: Include binary in target add-on container
FROM ${BUILD_FROM} AS runtime

RUN apt-get update
RUN apt-get install -y --no-install-recommends \
    bash \
    bluetooth \
    bluez \
    bluez-hcidump \
    bc \
    usbutils \
    git \
    curl \
    ca-certificates \
    mosquitto-clients

RUN git clone https://github.com/andrewjfreyer/monitor.git /monitor

# Prepare target folders
RUN mkdir /config

COPY run.sh /
RUN chmod +x /run.sh
ENTRYPOINT ["/run.sh"]

WORKDIR /monitor
CMD ["/bin/bash", "monitor.sh", "-D", "/config"]

#
# LABEL target docker image
#

# Build arguments
#ARG BUILD_ARCH
ARG BUILD_DATE
ARG BUILD_REF
ARG BUILD_VERSION

# Labels
LABEL \
    io.hass.name="Bluetooth Presence Monitor" \
    io.hass.description="Passive Bluetooth presence detection of beacons, cell phones, and other Bluetooth devices." \
#    io.hass.arch="${BUILD_ARCH}" \
    io.hass.type="addon" \
    io.hass.version=${BUILD_VERSION} \
    maintainer="Andrey Khrolenok <andrey@khrolenok.ru>" \
    org.label-schema.description="Passive Bluetooth presence detection of beacons, cell phones, and other Bluetooth devices." \
    org.label-schema.build-date=${BUILD_DATE} \
    org.label-schema.name="Presence_Monitor" \
    org.label-schema.schema-version="1.0" \
    org.label-schema.url="https://addons.community" \
    org.label-schema.usage="https://github.com/hassio-addons/addon-example/tree/master/README.md" \
    org.label-schema.vcs-ref=${BUILD_REF} \
    org.label-schema.vcs-url="https://github.com/hassio-addons/addon-example" \
    org.label-schema.vendor="Community Hass.io Addons"
