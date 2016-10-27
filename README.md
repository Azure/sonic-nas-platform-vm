sonic-nas-platform-vm
=====================

This repo contains virtual machine (VM) platform-specific files and implementation for the network abstraction service (NAS). The configuration files in this repo define port mapping, and so on.

Build
---------
See [sonic-nas-manifest](https://github.com/Azure/sonic-nas-manifest) for more information on common build tools.

### Build requirements
* `sonic-common-utils`
* `sonic-object-library`
* `sonic-base-model`
* `sonic-logging`
* `sonic-nas-ndi-api`

Copy the Debian files to the parent folder (default location of Debian files) and then run the `sonic_build` command.

BUILD CMD: sonic_build --dpkg libsonic-logging1 libsonic-logging-dev libsonic-common1 libsonic-common-dev libsonic-object-library1 libsonic-object-library-dev libsonic-model1 libsonic-model-dev sonic-ndi-api-dev -- clean binary

(c) Dell 2016
