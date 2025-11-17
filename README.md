# Veterix
Yet another fork of the Linux kernel by me

Based on Linux 2.4.37.11

this one however has a diffrent target in mind

and that's 80386 and other RAM limited machine types

Use with at the very least 12MB of RAM (16MB for better results),

2MB of Video RAM (for 16bit color mode in X Windows @ 1024x768),

2GB HDD Storage (if your BIOS can handle it)

FLDE (my desktop environment disigned for these systems)

uses IceWM

if your system has less than that specs than you will need use basic fvwm or ctwm instead

only use this if your card does not have enough Video RAM for the main FLDE

true supported minimums

12MB RAM

768KB* Video RAM (for 256 Color mode @ 1024x768)

*unsure about that amount id use 1MB to be safe

504MB HDD Storage

### Compiling and using for distribution's
depending on the arch i only officaly reccomend going like this:

80386: uClibc-ng, SysVinit

80486 and MIPS: musl, OpenRC

# Other Notices

> [!NOTE]
>
> This is assuming your using my fork of XFree86 3.3.6 as newer X versions used too much RAM
>
> So I am going to fork XFree86 3.3.6 and also try to patch that

> [!CAUTION]
> BEING A FORK OF LINUX 2.4.37.11,
>
> THERE ARE A LOT OF SECURITY HOLES RIGHT NOW THAT NEED PATCHING

> [!WARNING]
> I DO NOT HAVE A CRT DISPLAY TO TEST WITH SO I ASSUME THAT YOUR USING AN LCD
>
> Also I'm about to rebase this on Linux 1.2 because I Found it's 64bit support and in this project it's unnecessary as this is meant to have 386/486 clean
>
> Also that kernel version is more likely to be compatible with XFree86 3.3.6 (also forking that to make my own maintained version for this limited hardware)
