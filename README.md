SDCardPlayer8BitMono
====================
Introduction
============
The SDCardPlayer8BitMono is a Mono 8-bit WAV player based on the populat Simple SD Audio Player by Elm-Chan 

![sdcardplayer8bitmonobrd](https://cloud.githubusercontent.com/assets/5130298/7216016/efb87642-e5e6-11e4-9c0e-0a712c5cc24c.PNG)

Features
========
1. ATTINY85 microcontroller
2. Next track switch
3. Sound control
4. Power ON/OFF
5. Atmel Studio 6 programming file

Licence
=======
<p>This work is licensed under a <a href="http://www.creativecommons.org/licenses/by-sa/3.0" target="_blank">Creative Commons Attribution-ShareAlike 3.0 Unported License</a> 

Schematic
=========
![sdcardplayer8bitmonosch](https://cloud.githubusercontent.com/assets/5130298/7216017/1a1015a8-e5e7-11e4-94df-8e912ecf0967.PNG)

Programming File Fuse Settings - ATTINY85
=========================================
Blow fuses before flashing program code

1. SPIEN: tick
2. BODLEVEL: 2V7
3. SUT_CKSL: PLLCLK_1KCK_14CK_64MS
4. EXT:  FF
5. HIGH: DD
6. LOW:  E1
