# TGPKernel S8

![TGPKernel Logo](https://github.com/TheGalaxyProject/tgpkernel-s8-o/blob/master/build/logo.png?raw=true)

A Custom Kernel for Samsung Galaxy S8 / S8+

The main purpose of this Kernel is to have a stock-like Kernel that runs on S8 and S8+
variants, but capable of running S8+, N8 Port, and S9 Port Oreo Firmwares.

* XDA Unified S8 / S8+ Forum: http://forum.xda-developers.com/showthread.php?t=3654423
* Grifo Development Forum: https://forum.grifodev.ch/thread/96


Compiled using Google GCC 4.9 Toolchain

* URL: https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/aarch64/aarch64-linux-android-4.9

## How to use
Adjust the toolchain path in build.sh and Makefile to match the path on your system. 

Run build.sh with the following options, doesn't matter what order keep and silent are in.

- **./build.sh** will build TGPKernel
- **./build.sh -k** will build TGPKernel and also copy the .img files to the .output folder
- **./build.sh -s** will build TGPKernel but only display warning and errors in the log
- **./build.sh -ks** will do both **-k** and **-s** at the same time
- **./build.sh 0** will clear the workspace
- **./build.sh 00** will clear CCACHE

When finished, the new files and logs will be created in the .output directory.

If Java is installed, the .zip file will be signed.


## Credit and Thanks to the following:
- [Samsung Open Source Release Center](http://opensource.samsung.com) for the Source code
- [The Linux Kernel Archive](https://www.kernel.org) for the Linux Patches
- @osm0sis for [Android Image Kitchen](https://github.com/osm0sis/Android-Image-Kitchen/tree/AIK-Linux) and [anykernel2](https://github.com/osm0sis/AnyKernel2)
- @Tkkg1994, @morogoku, @Noxxxious, @farovitus, and @mwilky for help and commits

