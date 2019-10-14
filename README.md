# XBlast Lite CPLD

This package contains HDL project and PCB schematics of Xblast Lite device.

You will require Xilinx ISE software suite to generate programming files.
Constraint files included in project is made for accompagnating schematic.

Design aspire to offer a good balance between components pricing and ease of soldering.

Features include:

* 1MB flash support. Split as 512KB user bank, 256KB user bank, 256KB OS bank
* Full XBlast OS software support
* Parallel character LCD support, with backlight and contrast software control
* High-speed, high-current driver for D0(1.0-1.5) and LFRAME(1.6,1.6b)
* Chameleon/Matrix TSOP recovery (A15)
* Software-controlled TSOP split(1.0,1.1)
* General purpose inputs/outputs
* Status LED
* Chihiro mediaboard basic spoof (Reports as 1024MB FPGA mediaboard)
* Bank flashing & software control support in Evolution-X dashboard (Chameleon Modchip emulation)
* Support for 1.0-1.5 no solder adapter (D0 routing)
     
Have fun.