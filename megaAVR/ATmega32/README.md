# ATmega32 Platformio.ini file settings:

### General settings:
- F_CPU: 8000000L (8 Mhz)
- platform: atmelavr
- board: ATmega32

### Programmer:
- USBasp

### Fuse settings:
***link to fuse settings:  https://www.engbedded.com/fusecalc/***
- Int. RC Osc. 8 MHz; Start-up time: 6 CK + 64 ms; [CKSEL=0100 SUT=10]
- Brown-out detection disabled;
- Boot Flash section size=2048 words Boot start address=$3800; [BOOTSZ=00] ; default value
- Serial program downloading (SPI) enabled; [SPIEN=0]