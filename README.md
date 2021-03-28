General Information
===================

Linux driver for Realtek PCI-Express card reader chip.

Build Steps
===========

1) make
2) sudo make install
3) sudo depmod
4) sudo modprobe `rts5227`
5) check for kernel in use via `lspci -v`
