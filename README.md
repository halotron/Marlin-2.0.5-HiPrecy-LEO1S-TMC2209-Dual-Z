# Marlin 3D Printer Firmware

![GitHub](https://img.shields.io/github/license/marlinfirmware/marlin.svg)
![GitHub contributors](https://img.shields.io/github/contributors/marlinfirmware/marlin.svg)
![GitHub Release Date](https://img.shields.io/github/release-date/marlinfirmware/marlin.svg)
[![Build Status](https://github.com/MarlinFirmware/Marlin/workflows/CI/badge.svg?branch=bugfix-2.0.x)](https://github.com/MarlinFirmware/Marlin/actions)

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

Additional documentation can be found at the [Marlin Home Page](http://marlinfw.org/).
Please let us know if Marlin misbehaves in any way. Volunteers are standing by!

## HiPrecy LEO 1S

This repository fix some of the problems from the [original HiPrecy](https://github.com/HiPrecy)'s one and is intended to work with these specs:

* FYSETC F6 1.4 Motherboard
* TMC2209 Drivers
* Dual-Z Motors
* Bed Induction Probe

! Please note that the process is tested only with Arduino (<v2).

## Further info on building

Since F6_14 was a PR that never were merged to platformio, it seems that this will currently only be possible to build in arduino IDE. The current latest versuin 2.3.2 worked for me.
You need to install the TMCStepper library in the arduino ide to be able to compile.
You open the Marlin.ino file in the Marlin directory in arduino IDE.

This driver is for a stock Hiprecy Leo 1s having 2 z axis.

# As the stock Hiprecy Leo 1s does not have endstops, this version will instead rely on sensorless homing.

Arduino IDE 1.x works. Version 2+ does not work. Compilation problem.

