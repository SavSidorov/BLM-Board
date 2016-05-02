*Copyright UBC Formula Electric 2016.* 

*This documentation describes Open Hardware and is licensed under the CERN OHL v1.2.*

*You may redistribute and modify this documentation under the terms of the [CERN OHL v1.2](http://ohwr.org/cernohl). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY, AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN OHL v1.2 for applicable conditions.*

![BLM_2017 - Rev. A 3D Render (Top)](https://raw.githubusercontent.com/UBCFormulaElectric/BLM_2017-Board/master/Photos%20%26%20Renderings/BLM_2017%20-%20Rev.%20A%203D%20Rendering%20(Top).JPG)
*BLM_2017 - Rev. A 3D Render (Top)*

# Overview

The Brake Light Module (BLM_2017) is a brake light designed for our 2017 vehicle. It consists of a strip of 20 red chip LEDs and a Linear Technology LT3466 step-up LED driver.

The BLM is powered directly by the Drive Control Module (DCM_2017), which produces a +12V signal whenever either regeneration or the brakes are activated.

# Features

- The LEDs are split into two series strings of 10, each powered by a separate channel on the LED driver. This allows the brake light to still be clearly seen even in the event of a failure of one of the strings.
- The LED driver switching frequency can be adjusted by changing the value of resistor R1, and the current through each string can be set by modifying the feedback resistors R2 and R3.
- The two power wires are soldered directly to dedicated pads on the board. The intention is for the BLM to be housed in a 3D-printed waterproof enclosure, thereby eliminating the need for a bulky waterproof board-mount connector on the PCB itself.

![BLM_2017 - Rev. A (Top)](https://raw.githubusercontent.com/UBCFormulaElectric/BLM_2017-Board/master/Photos%20%26%20Renderings/BLM_2017%20-%20Rev.%20A%20%20(Top).jpg)
*BLM_2017 - Rev. A (Top)*
