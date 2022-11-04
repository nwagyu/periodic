# Periodic

[![Build](https://github.com/nwagyu/periodic/actions/workflows/build.yml/badge.svg)](https://github.com/nwagyu/periodic/actions/workflows/build.yml)

This app will show a [periodic table](https://en.wikipedia.org/wiki/Periodic_table) on your NumWorks calculator.

## Install the app

Installing is rather easy:
1. Download the latest `periodic.nwa` file from the [Releases](https://github.com/nwagyu/periodic/releases) page
2. Head to [my.numworks.com/apps](https://my.numworks.com/apps) to send the `nwa` file on your calculator

## How to use the app

Navigate around with the directional keys.

## Build and run the app

To build this sample app, you will need to install the [embedded ARM toolchain](https://developer.arm.com/Tools%20and%20Software/GNU%20Toolchain) and [nwlink](https://www.npmjs.com/package/nwlink).

```shell
brew install numworks/tap/arm-none-eabi-gcc node # Or equivalent on your OS
npm install -g nwlink
make run
```

This app is a port of [this app](https://github.com/UpsilonNumworks/Upsilon-External/tree/master/apps/Periodic).
