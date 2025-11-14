# Veterix
Yet another fork of the Linux kernel by me

Based on Linux 2.4.37.11

this one however has a diffrent target in mind

and that's 80386 and other RAM limited machine types

Use with at the very least 12MB of RAM,

1MB of Video RAM (for 16bit color mode in X Windows),

FLDE (my desktop environment disigned for these systems)

uses IceWM

if your system has less than that specs than you will need use basic MWM instead

### Compiling and using for distribution's
depending on the arch i only officaly reccomend going like this:

80386: uClibc-ng, SysVinit

80486 and MIPS: musl, OpenRC
