# Raspberrypi resources

This repo contains resources that you can use to set up your raspberrypi.

# /firmware

Here you'll find the fat32 partition **IMG** file(s) that you need to boot up your raspberry. If you're placing
your OS on a USB pen drive these minimal images are very fast to install.

```bash

# copy the boot image to the sdcard fat32 partition
dd if=2015-02-16-raspbian-wheezy-firmaware.img of=/dev/disk8s1

# edit the raspberrypi boot instruction to point it to the USB drive
# partition
vim cmdline.txt
...

```

## Links

* [Firmware upgrade post](http://blog.divhide.com/2015/03/08/raspberrypi-sdcard-boot-partition-images/)

## Authors

**Oscar Brito**

+ [github/aetheon](https://github.com/aetheon)
+ [twitter/aetheon](http://twitter.com/aetheon)

## License
Copyright (c) 2015 Oscar Brito <aetheon@gmail.com>, contributors.
Released under the  license
