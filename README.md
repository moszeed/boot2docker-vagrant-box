# boot2docker Vagrant Box

This repository contains the scripts necessary to create a Vagrant-compatible
[boot2docker](https://github.com/boot2docker/boot2docker) box.

## Usage

The box is available on
[Vagrant Cloud](https://vagrantcloud.com/codekitchen/boxes/boot2docker).
However, the box is designed to by used by [Dinghy](https://github.com/codekitchen/dinghy) to improve the Docker experience on OS X.

## Building the Box

If you want to recreate the box, rather than using the binary, then
you can use the scripts and Packer template within this repository to
do so in seconds.

To build the box, first install the following prerequisites:

  * [Packer](http://www.packer.io) (at least version 0.7.2)
  * [VirtualBox](http://www.virtualbox.org) (at least version 4.3), VMware, or Parallels
  * [Make](http://www.gnu.org/software/make/)
  * [wget](http://www.gnu.org/software/wget/)

Then follow the steps:

```
$ make
...
```
