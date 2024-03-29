# MDCtrl
DIY simple and ultraportable controller powered by [GP2040-CE Firmware](https://github.com/OpenStickCommunity/GP2040-CE)

![Finished MDCtrl](Assets/images/finished.jpg)
---

# BOM

The component that you need to build MDCtrl:
- MDCtrl [PCB](/Ver1/pcb/)
- MDCtrl Case [(2D)](/Case/)
- Raspberry Pi Pico 
- **12** Kailh hotswap sockets (Optional)
- **12** Keyboard switches
- **12** Keycaps
- **1** Stabilizer
- **5** 6x6x5 [Tactile Switches](https://www.hdk.co.jp/pdf/eng/e291702.pdf)
- Soldering component
- Rubber Feet (For the bottom of the case)

PCB thickness should be 1,6mm (Double layer) with masking color of your choice


# Board

Board Version |   [Ver1](/Ver1/)  |  [Ver2 (WIP)](/Ver2/)  |
--------------|:-----------------:|:----------------:|
PCB Dimension | 175,418x87,312mm  | WIP              |
Board Used    | [Raspberry Pi Pico](https://www.raspberrypi.com/products/raspberry-pi-pico/) | [Waveshare RP2040-Zero](https://www.waveshare.com/rp2040-zero.htm)|
Port          | Micro USB         | USB-C            |




# Sources

PCB Design built with the following sources:
- [Firmware GP2040-CE](https://github.com/OpenStickCommunity/GP2040-CE)
- [Raspberry Pi Pico Footprint by Nicolò Carandini](https://github.com/ncarandini/KiCad-RP-Pico)
- [Keyboard Switches Footprint](https://github.com/ebastler/marbastlib)

---

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
