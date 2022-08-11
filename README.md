CPCCartridge
============

This repository will contain two projects to create a Amstrad Plus / Amstrad GX4000 cartridge.
The first will be a simple cartridge with a ZIF socket, to enable you to change the ROM easily.
The second will be a bit of a reverse engineering of a 30-in-1 cartridge.


Simple Cartridge
================

In the "simple-cartridge" folder, you will find the schematics and board layout for a simple flash
cartridge for the Amstrad Plus / Amstrad GX4000 cartridge. You can equip it either with an CPLD
(XC9536) with ACID protection emulation (see http://www.octoate.de/wp/articles/acid-verilog-code/
for more information) or a real ACID protection chip. It uses an AT29F040 to store the ROM data.


30-in-1 Cartridge
=================

A Xilinx XC9536 VQFP is used for ACID protection emulation, once it is perfected and tested in the
Simple Cartridge.


KiCAD Library
=============

The folder "library" just contains a library for KiCAD footprints and models
which contains the layout of a Amstrad Plus / Amstrad GX4000 cartridge.


ACID protection emulation
=========================

The "emulation" folder contains the Verilog description for the ACID protection, which you can use
to program a CPLD or an FPGA with the dedicated design tools. For more information about the emulation
you can visit http://www.octoate.de/wp/articles/acid-verilog-code


This Repo is a fork of
(c)2010-2014 Tim Riemann aka Octoate
