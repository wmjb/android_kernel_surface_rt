# android_kernel_surface_rt

make ARCH=arm tegra3_android_defconfig
make ARCH=arm CROSS_COMPILE=arm-none-eabi- -j $(nproc)
