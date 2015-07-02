## SparkFun SparkFun's Serial Graphic LCD Backpack Particle Library

Firmware library for SparkFun's Serial Graphic LCD Backpack.

About
-------------------

This is a firmware library for [SparkFun's Serial Graphic LCD Backpack](https://www.sparkfun.com/products/9352).

[![SparkFun's Serial Graphic LCD Backpack](https://cdn.sparkfun.com//assets/parts/2/9/2/2/09352-01.jpg)](https://www.sparkfun.com/products/9352).

This is the serial backpack for graphic LCDs. The SparkFun Graphic LCD Serial Backpack interfaces to either our 160x128 pixel “Huge” Graphic LCD, or the smaller 128x64 pixel display, and provides a simple serial interface to a full range of controls.

This backpack will allow you to write text, draw lines, circles and boxes, set or reset individual pixels, and erase specific blocks of the display. The backlight and baud rate can also be controlled via serial communication. There’s also a reverse mode that allows the screen to operate blue on white instead of white on blue. Additionally, all source code for the ATMega168 processor is compiled using the free WinAVR compiler and is free for downloading.

Repository Contents
-------------------

* **/doc** - Additional documentation for the user. These files are ignored by the IDE. 
* **/firmware** - Source files for the library (.cpp, .h).
* **/firmware/examples** - Example sketches for the library (.cpp). Run these from the Particle IDE. 
* **spark.json** - General library properties for the Particel library manager. 

Example Usage
-------------------

Include the Serial Graphic LCD library:

	#include "SparkFunMPL3115A2.h" // Include the SparkFun MPL3115A2 library

Recommended Components
-------------------

* [Particle Photon](https://www.sparkfun.com/products/13345)
* [SparkFun Serial Graphic LCD 160x128](https://www.sparkfun.com/products/8884)
* [SparkFun Serial Graphic LCD 128x64](https://www.sparkfun.com/products/9351)

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact techsupport@sparkfun.com.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
