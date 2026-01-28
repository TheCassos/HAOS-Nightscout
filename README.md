# Home Assistant Add-ons repository

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

The primary goal of this project is to provide you (as a Home Assistant user)
with additional, high quality, add-ons that allow you to take your automated
home to the next level.

## Installation

In general, there is no need to install this repository on your
Home Assistant instance. It is activated and added by Home Assistant
by default.

However, if the repository is missing on your setup, adding this add-ons
repository to your Home Assistant instance is pretty easy. In the
Home Assistant add-on store, a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/achkars/addons-repository
```

## Add-ons provided by this repository

### &#10003; [Nightscout][addon-nightscout]

![Latest Version][nightscout-version-shield]
![Supports armhf Architecture][nightscout-armhf-shield]
![Supports armv7 Architecture][nightscout-armv7-shield]
![Supports aarch64 Architecture][nightscout-aarch64-shield]
![Supports amd64 Architecture][nightscout-amd64-shield]
![Supports i386 Architecture][nightscout-i386-shield]
![Docker Pulls][nightscout-pulls-shield]

Nightscout acts as a web-based CGM (Continuous Glucose Montinor) to allow multiple caregivers to remotely view a patients glucose data in realtime.

[:books: Nightscout add-on documentation][addon-doc-nightscout]


[addon-nightscout]: https://github.com/achkars/addon-nightscout/releases/tag/v1.4.1
[addon-doc-nightscout]: https://github.com/achkars/addon-nightscout/blob/v1.4.1/README.md
[nightscout-issue]: https://github.com/achkars/addon-nightscout/issues
[nightscout-version-shield]: https://img.shields.io/badge/version-v1.4.1-blue.svg
[nightscout-pulls-shield]: https://img.shields.io/docker/pulls/achkars/image-amd64-addon-nightscout.svg
[nightscout-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[nightscout-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[nightscout-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[nightscout-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[nightscout-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
