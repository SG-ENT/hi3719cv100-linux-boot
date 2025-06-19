# Hi3719CV100 Linux Boot Files

This repository contains bootloader-level images for HiSilicon Hi3719CV100 TFTP boot.

## Included Files
- `uImage`: Linux kernel image
- `hi3719cv100.dtb`: Device tree blob
- `initrd.img`: Initrd with BusyBox + SSH
- `uEnv.txt`: U-Boot boot configuration

## Usage
Use TFTP to load these from U-Boot, or flash to NAND as needed.
