## HiPrecy LEO 1S

This repository fix some of the problems from the [original HiPrecy](https://github.com/HiPrecy)'s one and is intended to work with these specs:

- FYSETC F6 1.4 Motherboard
- TMC2209 Drivers
- Dual-Z Motors
- Bed Induction Probe
- No endstops

! Please note that the process is tested only with Arduino (<v2).

## Further info on building

Since F6_14 was a PR that never were merged to platformio, it seems that this will currently only be possible to build in arduino IDE.
You need to install the TMCStepper library in the arduino ide to be able to compile.
You open the Marlin.ino file in the Marlin directory in arduino IDE.

This driver is for a stock Hiprecy Leo 1s having 2 z axis.

# As the stock Hiprecy Leo 1s does not have endstops, this version will instead rely on sensorless homing.

Arduino IDE 1.x works. Version 2+ does not work. Compilation problem.
