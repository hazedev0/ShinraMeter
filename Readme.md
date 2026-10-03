Shinra Meter
==============

This is a fork of [neowutran's ShinraMeter](https://github.com/neowutran/ShinraMeter), maintained by
hazedev0.

It's made for and tested on **Agaia (EU, English client)**. Its game data comes from the
[TeraDpsMeterData fork](https://github.com/hazedev0/TeraDpsMeterData), extracted from Agaia's EU client,
so on other servers or with other client languages names and icons may be missing or wrong. Unlike the
original, it doesn't upload fight results anywhere.

Install it as a TERA Toolbox module: save
[module.json](https://raw.githubusercontent.com/hazedev0/shinra-toolbox-release/master/module.json) into
`mods\shinra-meter` in your Toolbox folder (replacing the old one, if any) and start Toolbox.

Report bugs at https://github.com/hazedev0/ShinraMeter/issues.

The rest of this readme is from the original project.

[<img src="https://img.shields.io/badge/rating-4%2B%20stars-brightgreen.svg">](https://recordnotfound.com/ShinraMeter-neowutran-9937)

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/yukikoo)

ShinraMeter is a DPS Meter for TERA based off https://github.com/gothos-folly/TeraDamageMeter . 

Wiki: https://github.com/neowutran/TeraDamageMeter/wiki

Download: https://neowutran.ovh/updates/

TERADATA: https://github.com/neowutran/TeraDpsMeterData

https://neowutran.ovh/teraDB/

ShinraMeter is dev by Gl0 and Yukikoo/Neowutran
 

Logo
---------
 
Thanks to Se7en-Hellas for the new Shinra logo =) 

Se7en-Hellas website: http://se7enhellas.wixsite.com/mylogogr 

Shinra Manager by Dark (external contributor) 
---------------
https://github.com/SaltyMonkey/ShinraManager

Cool UI project by Foglio
-------------------
https://github.com/Foglio1024/Tera-custom-cooldowns

Somehow related project
--------------------
https://github.com/neowutran/S1UI_GPU

https://github.com/neowutran/S1UI_chat2


Original Readme
================


TeraSniffer and Damage Meter by Gothos.

* Packet encryption code and the list of server IPs are from

  https://github.com/GoneUp/Tera_PacketViewer

  Thanks to GoneUp and whoever else worked on this.

* Skillnames extracted from:

  https://forum.ragezone.com/f797/release-tera-datacenter-unpacked-eur-1064404/

  Thanks to mangojoe for the dumps

  Used a modified version of DataTools to extract the list from this dump.

* TeraEmulator was very helpful for understanding the packet structures.

   https://github.com/r4ymonf/TeraEmulator

OpCodes dumped by GoneUp, Gothos, dezmen
