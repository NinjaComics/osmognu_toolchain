osmognu_toolchain
=================

This repo consists of a working toolchain to run osmocomBB(layer1) on target
calypso boards. The buildscript is a copy of the script found at [osmocomBB Wiki]
(http://bb.osmocom.org/trac/wiki/GnuArmToolchain), with minimal tweaks to
compiler, linker and C library versions. Note that gcc-4.6.4 used to build the
arm-elf-gcc is the last version of gcc to support the arm-elf binary format.
To use the toolchain, fork this repo, clone it and add the /bin directory to the
.bashrc.





