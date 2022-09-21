HydraNFC Shield v1 and HydraNFC Antenna
========

HydraNFC hardware shield v1
![HydraNFC shield](HydraNFC_board.jpg)

The HydraNFC is an NFC shield hardware to sniff, read/write or emulate any 13.56MHz NFC tags for anyone interested in debugging/hacking/developing for NFC.
It has been designed to be used with HydraBus see https://github.com/hydrabus/hydrabus but can also be used with other MCU.

You can Buy HydraBus/HydraNFC Online: http://hydrabus.com/buy-online

Open source code firmware(For HydraBus), is available see
https://github.com/hydrabus/hydrafw

Wiki for HydraFW: https://github.com/hydrabus/hydrafw/wiki

Tutorial with HydraBus + HydraNFC  (using HydraFW v0.5 beta):
* Initialize GPIO & SPI to communicate with TRF7970A/HydraNFC
* Initialize & read ISO15693/Vicinity Tag
* Initialize & read ISO14443A/Mifare Tag
* Use TRF7970A commands (SLOS743K – August 2011 – revised April 2014)
* For more details see 
https://github.com/hydrabus/hydrafw/wiki/HydraFW-HydraNFC-v1-guide
https://github.com/hydrabus/hydrafw/wiki/HydraFW-HydraNFC-v1.x-TRF7970A-Tutorial

Tutorial to use HydraNFC and understand how work the NFC chipset (TRF7970A) with BusPirate or any other hardware with SPI:
* See http://bvernoux.blogspot.fr/2012/01/nfc-ti-trf7970a-breakout-board-v10-for.html

For more details on the hardware see also http://hydrabus.com/hydranfc-1-0-specifications
