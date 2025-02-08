## What is this?

This is an ultra configured and optimized .config file for IvyBridge CPUs (Optimized specifically for I7-3770, but will work With the I5 and the I3).

At this time, This .config file was made on 6.13.0 kernel version, Will update it when new kernels release.

## Installation

1. Open The Terminal.

2. Apply These Commands.

```shell
cd Downloads
git clone https://github.com/xSqr1/Linux-dot-config-i7-3770.git
cd Linux-dot-config-i7-3770
```

3. Copy The .config file to your linux kernel folder.

4. Delete the existing .config file in your linux kernel folder.

5. Paste the configured .config to your kernel path.

That's it, Enjoy having less ram usage, with better Performance.


## Extra

If You want even more, You can apply some patches to the kernel To get even better performance.

To apply a patch, Paste this command:

```shell
cd /path/to/your/linuxkernel 
patch -p1 < /path/to/your/patch.patch
```


1. All cpu Architectures patch: https://github.com/Diab1e/Linux-Kernel-Compiler-Patch.git

2. Optimize O3 Harder patch (Gives Better performance): https://github.com/Frogging-Family/linux-tkg.git

3. Project C PDS/BMQ cpu shceduler patch: https://gitlab.com/alfredchen/projectc.git

**All Of these patches improves the kernel performance.**


## NOTE


**THIS .CONFIG FILE IS HARSHLY OPTIMIZED FOR ULTRA PERFORMANCE AND LOWEST RAM USAGE POSSIBLE, SO THINGS LIKE "BLUETOOTH, PRINTERS" WILL NOT WORK.**
