# Limych's Hass.io Add-ons for Home Assistant

![Project Stage][project-stage-shield]
![Project Maintenance](https://img.shields.io/badge/maintainer-Andrey%20Khrolenok%20%40Limych-blue.svg)
[![License][license-shield]](LICENSE)

## About

Hass.io allows anyone to create add-on repositories to share their add-ons for
Hass.io easily. This repository is one of those repositories, providing extra
Home Assistant add-ons for your Hass.io installation.

The primary goal of this project is to provide you (as a Hass.io /
Home Assistant user) with additional, high quality, add-ons that allow you to
take your automated home to the next level.

## Installation

Adding this add-ons repository to your Hass.io Home Assistant instance is
pretty easy. Follow [the official instructions][third-party-addons] on the
website of Home Assistant, and use the following URL:

```txt
https://github.com/Limych/hassio-addons
```

## Add-ons provided by this repository

### &#10003; [Bluetooth Presence Monitor][addon-presence-monitor]

![Latest Version][presence-monitor-version-shield]
![Supports armhf Architecture][presence-monitor-armhf-shield]
![Supports armv7 Architecture][presence-monitor-armv7-shield]
![Supports aarch64 Architecture][presence-monitor-aarch64-shield]
![Supports amd64 Architecture][presence-monitor-amd64-shield]
![Supports i386 Architecture][presence-monitor-i386-shield]
![Docker Pulls][presence-monitor-pulls-shield]

Passive Bluetooth presence detection of beacons, cell phones, and other Bluetooth devices.

* [:open_file_folder: Bluetooth Presence Monitor add-on files tree][addon-tree-presence-monitor]
* [:books: Bluetooth Presence Monitor add-on documentation][addon-doc-presence-monitor]

### &#10003; [Bluetooth Presence Monitor (edge)][addon-presence-monitor-edge]

![Latest Version][presence-monitor-edge-version-shield]
![Supports armhf Architecture][presence-monitor-edge-armhf-shield]
![Supports armv7 Architecture][presence-monitor-edge-armv7-shield]
![Supports aarch64 Architecture][presence-monitor-edge-aarch64-shield]
![Supports amd64 Architecture][presence-monitor-edge-amd64-shield]
![Supports i386 Architecture][presence-monitor-edge-i386-shield]
![Docker Pulls][presence-monitor-edge-pulls-shield]

Passive Bluetooth presence detection of beacons, cell phones, and other Bluetooth devices.

* [:open_file_folder: Bluetooth Presence Monitor (edge) add-on files tree][addon-tree-presence-monitor-edge]
* [:books: Bluetooth Presence Monitor (edge) add-on documentation][addon-doc-presence-monitor-edge]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

Follow to The Home Assistant [Community Forum][forum].

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Bluetooth Presence Monitor][presence-monitor-issue]
- [Open an issue for the add-on: Bluetooth Presence Monitor (edge)][presence-monitor-edge-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## License

MIT License

Copyright (c) 2019-2020 Andrey "Limych" Khrolenok

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-presence-monitor]: https://github.com/Limych/hassio-addons/tree/master/presence-monitor
[addon-tree-presence-monitor]: https://github.com/Limych/addon-presence-monitor/tree/v1.0.0
[addon-doc-presence-monitor]: https://github.com/Limych/addon-presence-monitor/blob/v1.0.0/README.md
[presence-monitor-issue]: https://github.com/Limych/addon-presence-monitor/issues
[presence-monitor-version-shield]: https://img.shields.io/badge/version-v1.0.0-blue.svg
[presence-monitor-pulls-shield]: https://img.shields.io/docker/pulls/limych/hassio-presence-monitor-armv7.svg
[presence-monitor-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[presence-monitor-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[presence-monitor-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[presence-monitor-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[presence-monitor-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[addon-presence-monitor-edge]: https://github.com/Limych/hassio-addons/tree/master/presence-monitor-edge
[addon-tree-presence-monitor-edge]: https://github.com/Limych/addon-presence-monitor/tree/3940db0
[addon-doc-presence-monitor-edge]: https://github.com/Limych/addon-presence-monitor/blob/3940db0/README.md
[presence-monitor-edge-issue]: https://github.com/Limych/addon-presence-monitor/issues
[presence-monitor-edge-version-shield]: https://img.shields.io/badge/version-3940db0-blue.svg
[presence-monitor-edge-pulls-shield]: https://img.shields.io/docker/pulls/limych/hassio-presence-monitor-armv7.svg
[presence-monitor-edge-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[presence-monitor-edge-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[presence-monitor-edge-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[presence-monitor-edge-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[presence-monitor-edge-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io?u=limych
[issue]: https://github.com/Limych/hassio-addons/issues
[license-shield]: https://img.shields.io/github/license/Limych/hassio-addons.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html
[third-party-addons]: https://www.home-assistant.io/hassio/installing_third_party_addons/