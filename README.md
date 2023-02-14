# android_kernel_surface_rt

Ubuntu Xenial



make ARCH=arm surface-rt_linux_defconfig

make ARCH=arm CROSS_COMPILE=arm-none-eabi- -j $(nproc)
