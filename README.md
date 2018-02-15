# Pandaboard Gadget Snap

[![Snap Status](https://build.snapcraft.io/badge/ThyMYthOS/panda-gadget.svg)](https://build.snapcraft.io/user/ThyMYthOS/panda-gadget)

This repository contains the source for an Ubuntu Core gadget snap for the Pandaboard.

Building it with snapcraft will automatically pull, configure, patch and build
the git.denx.de/u-boot.git upstream source for omap4_panda_defconfig at release v2017.01,
produce a MLO, u-boot.img binary and uboot.env and put it inside the gadget.


## Gadget Snaps

Gadget snaps are a special type of snaps that contain device specific support
code and data. You can read more about them in the snapd wiki
https://github.com/snapcore/snapd/wiki/Gadget-snap

## Reporting Issues

Please report all issues on the Github project page
https://github.com/ThyMYthOS/panda-gadget/issues

## Building

To build the gadget snap locally on an armhf system please use `snapcraft`.

To cross build this gadget snap on a PC please install the gcc-arm-linux-gnueabihf package
before running `snapcraft`.

## Automatic Builds

The master branch is automatically built by https://build.snapcraft.io and
published into the snap store to the edge channel.
