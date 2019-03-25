# Avrcpm2.2
Cp/m 2.2 on AVR stick revision 3.1

See the full project at https://www.mikrocontroller.net/topic/177481?page=4#3941030

# avrcpm
Originally by sprite_tm and further developed by german mikrocontroller forum.

![screen](https://github.com/petersieg/avrcpm/blob/master/screen.jpg)

![stick](https://github.com/petersieg/avrcpm/blob/master/stick.jpg)


avrcpm.hex is ready to be flashed to 328P running at 20MHz and communicates with 9600 8N1.

Use the m328 batch script for windows users

Build system. Format sd card with fat16 and copy CPMDSK_A.IMG on root dir on it. Boot.

The following DRAM devices (256k x 4bit) have been successfully tested with hardware variant 3 at 20 MHz system clock:

AAA1M304 70ns

GM71C4256 60ns

HY51C4256 100ns

HY534256 70ns / 80ns / 100ns

HYB514256 70ns

KM44C256 70ns

M514256 70ns / 80ns

M5M44256 80ns

MB81C4256 70ns

MT4C4M4B1DJ-6 / 60ns

V53C104 45ns / 60ns / 80ns

The following blocks may not run:

SIEMENS HYB514256B-70

The following SD cards have been tested successfully with the hardware variant 3 at 20 MHz system clock:

CnMemory (FIRSTCLASS) 1GB
Intenso 2GB
Kingston 1GB
Panasonic 2GB Class 4
SK 4GB SDHC Class 6
Traveler 64MB

Links:

http://spritesmods.com/?art=avrcpm

http://www.mikrocontroller.net/topic/177481

http://www.mikrocontroller.net/articles/AVR_CP/M




