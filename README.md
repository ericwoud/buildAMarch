# buildAMarch

Image file for OLIMEX AM3352 / AM3359 board running archlinux and linux 6.12

Linux package here:

https://github.com/ericwoud/archlinuxarm-repo/tree/linux-am335x-git

Linux package can be build on x86-64 machine also.

See releases for image file.

Use command:
```
xz -dc am3359.img.xz | dd of=/dev/device status=progress
```
