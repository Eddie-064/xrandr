import from:
https://gitlab.freedesktop.org/xorg/app/xrandr.git

sudo apt-get install autoconf automake libtool

sudo apt-get install pkg-config

sudo apt-get install xorg-dev

reference: 

https://bbs.archlinux.org/viewtopic.php?id=227738

https://github.com/merge/xf86-input-tslib/issues/9


build steps:

./autogen.sh

./configure

make



xrandr - primitive command line interface to X11 Resize, Rotate, and Reflect
(RandR) extension

All questions regarding this software should be directed at the
Xorg mailing list:

  https://lists.x.org/mailman/listinfo/xorg

The master development code repository can be found at:

  https://gitlab.freedesktop.org/xorg/app/xrandr

Please submit bug reports and requests to merge patches there.

For patch submission instructions, see:

  https://www.x.org/wiki/Development/Documentation/SubmittingPatches

