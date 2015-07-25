AdvanceMAME/MESS emulators and AdvanceMENU frontend
===================================================

AdvanceMAME/MESS are unofficial MAME/MESS versions with an
advanced video support for helping the use with TVs, Arcade
monitors, PC monitors and LCD screens.

AdvanceMENU is a frontend for the AdvanceMAME, AdvanceMESS, MAME,
MESS and any other emulator.

They run in Linux, Mac OS X, DOS, Windows and in all the other
platforms supported by the SDL library.

The official site of AdvanceMAME/MESS is :

    http://www.advancemame.it/

RetroPie
--------
To compile use the following configure options (change prefix accordingly):
```shell
./configure CFLAGS="-pipe -O2 -mcpu=cortex-a7 -mfpu=neon-vfpv4 -mfloat-abi=hard -fsigned-char" LDFLAGS="-s -lm -Wl,--no-as-needed" --prefix="/opt/retropie/emulators/advmame/1.3"
```
