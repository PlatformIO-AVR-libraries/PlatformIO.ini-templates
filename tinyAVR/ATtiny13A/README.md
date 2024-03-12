# ATtiny13A Platformio.ini file settings:

### General settings:
- F_CPU: 9600000L (9.6 Mhz)
- platform: atmelavr
- board: ATtiny13A

### Programmer:
- USBasp

### Fuse settings:
***link to fuse settings:  https://www.engbedded.com/fusecalc/***
- Int. RC Osc. 9.6 MHz; Start-up time: 14 CK + 64 ms; [CKSEL=10 SUT=10]; default value
- Serial program downloading (SPI) enabled; [SPIEN=0]
- Brown-out detection disabled; [BODLEVEL=11]