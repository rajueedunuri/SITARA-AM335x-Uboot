# uboot
u-boot 2019 source code repository to support Beagle Bone Black.
# U-Boot for TI Sitara AM335x (BeagleBone Black)

This repository contains the U-Boot bootloader source code for the
TI Sitara AM335x processor family, specifically targeted for the
BeagleBone Black platform.

## Purpose
U-Boot is responsible for:
- Hardware initialization
- DDR memory setup
- Loading the Linux kernel and device tree
- Providing boot options via environment variables

This repository is maintained as part of a custom Embedded Linux
Board Support Package (BSP) for AM335x.

## Features
- AM335x / BeagleBone Black support
- Custom board configuration
- Boot from MMC / eMMC / SD
- Environment support
- Device Tree based booting

## Directory Overview
- `arch/`      – Architecture-specific code (ARM)
- `board/`     – Board-level initialization
- `configs/`   – Board configuration files
- `drivers/`   – Peripheral drivers
- `include/`   – Header files

## Build (example)
```bash
make am335x_boneblack_defconfig
make
