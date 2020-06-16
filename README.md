# E-27 Line Sensor

**Project Status:** Prototype

If you are new to GitHub and would like to create a derivative of this project, please have a look at GitHub instructions to [fork a repo](https://help.github.com/en/articles/fork-a-repo)

## Description

Out of our passion to solve the issue of time waste in the robot creation process, ARC was born. The ARC software platform reduces the time it takes to get from idea to implementation. Since 2011 we have been listening to the challenges robot builders encounter and continue to provide them with an ever expanding toolbox of solutions. Join us on this journey!

We didn't stop at the software, we also made time saving hardware solutions. This Line sensor reference design is one of them. This sensor can be used for Line following, edge detection, gesture control, or any number of other applications that can utilize a reflective infrared sensor. We want to share these files with you so you can create your own version for your community and customers to enjoy!

**Features:**
- I2C communication
- Green Power LED
- Mini PIC programming port
- 3 x Refective optical sensors 18mm apart for Line sensing
- Alternatively use this reference design for Gesture sensing as sensor values are variable
- Voltage requirement: 3.2-3.4V (3.3V typical)
- Current draw: 35.3mA
- Dimensions: 43(W) x 43.5(L) x 10.3(H) (mm)
- Weight: 6g

**Major components:** 
- PIC16F1704-I/ST PIC Microcontroller (custom firmware provided)
- 3 x TCRT5000L Reflective Optical Sensor with Transistor Output

**Manufacturing notes:** 
1. Supplier: programs custom firmware into the PIC16F1704-I/ST at their facility before sending to manufacturer
2. Manufacturer: Single side placement and soldering of SMT components
3. Manufacturer: Single Side soldering of THT components

## Contents

[**Documentation:**](https://github.com/synthiam/E-27_Line_Sensor/tree/master/E-27%20Documentation) Schematic PDF, Datasheet PDF, BOM

[**Hardware:**](https://github.com/synthiam/E-27_Line_Sensor/tree/master/E-27%20Hardware) Altium PCB design File, Altium SCH Design File

*Altium Libraries are also available <a href="https://github.com/synthiam/Synthiam_Altium_Librairies">here</a>*

## Photos

<p align="left">
<img src="https://live.staticflickr.com/65535/32801180957_0ac42a03d9_k.jpg" width="683" height="383">
<img src="https://live.staticflickr.com/65535/40778037073_3a07ccc2b5_k.jpg" width="683" height="383"></p>

## Contact

For profit use of these files requires written consent. Contact partners@synthiam.com. For everyone else, party on!

Synthiam Website: https://synthiam.com

## License

This project is released under the following licenses:

**Hardware:** Creative Commons Plus Attribution-NonCommercial 4.0 International (CC+ BY-NC 4.0)

**Firmware:** Apache 2.0 + “Commons Clause” License Condition v1.0

Please see [LICENSE.md](https://github.com/synthiam/E-27_Line_Sensor/blob/master/LICENSE.md) for license details.

<a href="https://synthiam.com"><img src="https://live.staticflickr.com/65535/47791527651_358dffb302_m.jpg"></a>
