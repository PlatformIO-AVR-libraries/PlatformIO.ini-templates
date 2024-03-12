# ATtiny2313 Platformio.ini file settings:

### General settings:
- F_CPU: 8000000L (8 Mhz)
- platform: atmelavr
- board: ATtiny2313

### Programmer:
- USBasp

### Fuse settings:
***link to fuse settings:  https://www.engbedded.com/fusecalc/***
- Int. RC Osc. 8 MHz; Start-up time: 14 CK + 65  ms; [CKSEL=0100 SUT=10]; default value
- Brown-out detection disabled; [BODLEVEL=111]
- Serial program downloading (SPI) enabled; [SPIEN=0]