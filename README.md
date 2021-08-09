# kernel-tools
Tools for compiling and updating Gentoo's kernel

## grub-update
Simply replace common `grub-mkconfig -o /boot/grub/grub.cfg` command to update Grub bootloader

## build-kernel
Tool to build an updated kernel from current or choosen kernel configuration
Use `build--kernel --help` for more information

# Installation instruction
The preferred way to install these Gentoo's kernel-tools is to add [overlay](https://github.com/Anard/anard-overlay) and `# emerge -a kernel-tools`

It's also possible to clone this repository and copy scripts in /usr/sbin
