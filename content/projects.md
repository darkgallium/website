---
title: "Projects"
draft: false
---

## Software

### Current

* [confinebot](https://github.com/InsaLan/confinebot), a more modern alternative to the famous eBot CS:GO match manager.

* [arduino-u2fhid](https://github.com/darkgallium/arduino-u2fhid), an effort to make a U2F FIDO compatible key from an Arduino Micro. Turns out the Arduino isn’t fast enough to implement the protocol (especially generate the ECDSA keys). I will try to port the code to ESP32 *soon* :) 

### Past

* a [port](https://github.com/darkgallium/openwrt/tree/tl-850re-v2-backport1701) of LEDE 17.01 for my TP Link TL-850re v2 wifi AP (device with a NAND flash of only 4 MB). Not quite working at this time, device boots, failsafe mode works (luckily) but wifi & ethernet don't in normal mode.

* [mini](https://git.deuxfleurs.fr/darkgallium/mini), a minimal init system written in Rust (my first project in this language!). Its main set of features is nearly complete, it just lacks start/stop services support.

* [langate2000](https://github.com/insalan/langate2000): a captive portal written in **Python** that authenticates users on the network, used at the InsaLan event. I was in charge of the frontend and some backend code.

* rainbow, a distributed rainbow table implementation written in **C** using the **OpenMPI** library, made as part of an internship at IRISA, supervised by Pr. Gildas Avoine.

## Talks

* 2021: Organizing a LAN-party in 2021 (rump at [barbhack](https://www.barbhack.fr/) 2021, french): a small 5min presentation of the technical side of [InsaLan](https://www.insalan.fr), [slides](/rump-barbhack-2021/).

* 2019: Initial network training (french): some [slides](/formation-reseau-1/) to give a minimal background for the newcomers in the network team at [InsaLan](https://www.insalan.fr).
