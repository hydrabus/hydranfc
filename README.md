HydraNFC Shield and HydraNFC Antenna
========

HydraNFC hardware shield
![HydraNFC shield](HydraNFC_board.jpg)

The HydraNFC is an NFC shield hardware to sniff, read/write or emulate any 13.56MHz NFC tags for anyone interested in debugging/hacking/developing for NFC.
It has been designed to be used with HydraBus see https://github.com/bvernoux/hydrabus but can also be used with other MCU.

You can Buy HydraBus/HydraNFC Online in Seeed Studio Online Shop: http://www.seeedstudio.com/depot/HydraBus-m-132.html

Open source code firmware(For HydraBus), is available see
https://github.com/bvernoux/hydrafw

Wiki for HydraFW: https://github.com/bvernoux/hydrafw/wiki

Tutorial with HydraBus + HydraNFC  (using HydraFW v0.5 beta):
 * Initialize GPIO & SPI to communicate with TRF7970A/HydraNFC
 * Initialize & read ISO15693/Vicinity Tag
 * Initialize & read ISO14443A/Mifare Tag
 * Use TRF7970A commands (SLOS743K – August 2011 – revised April 2014)
See https://github.com/bvernoux/hydrafw/wiki/HydraFW-HydraNFC-TRF7970A-Tutorial

Tutorial to use HydraNFC and understand how work the NFC chipset (TRF7970A) with BusPirate or any other hardware with SPI:
http://bvernoux.blogspot.fr/2012/01/nfc-ti-trf7970a-breakout-board-v10-for.html

For more details on the hardware see also http://hydrabus.com/hydranfc-1-0-specifications
