# Jetson-buildroot
Source tree for application development based on Jetson nano

# Guide
To build and use the buildroot stuff, do the following:

1. run 'make aarch64_mai_defconfig'
2. run 'make'
3. wait while it compiles
4. find the kernel, bootloader, root filesystem, etc. in output/images

You do not need to be root to build or run buildroot. Have fun!

# References:
1. Source code - hash commit: 572c7af8dbcc9539ea54724e88b0850ae47d98ee
https://github.com/buildroot/buildroot 
2. Config refers from D3_growe: 
https://devtalk.nvidia.com/default/topic/1046993/jetson-agx-xavier/embedded-linux/post/5318527/#5318527
