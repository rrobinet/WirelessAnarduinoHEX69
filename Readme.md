# * ~~~ Obsolete ~~~ *
From _Felix Russu_ Moteino´s Library:

>> This library is obsolete and no longer supported. The Wireless Programming protocol was mergerd in the mainstream [RFM69 library](https://github.com/LowPowerLab/RFM69) and now known as **RFM69_OTA.h** - so replace/include that instead of **WirelessHEX69.h** in any new sketches. There are new [Programmer and Target examples](https://github.com/LowPowerLab/RFM69/tree/master/Examples/WirelessProgramming_OTA) in the main RFM69 lib as well.
<br>**WirelessProgramming.exe** has also been upgraded and included at the link above and the one in this directory is kept for reference but is no longer up to date to be used with the latest RFM69_OTA library.

This library is not compatible with new version of [RFM69 library](https://github.com/LowPowerLab/RFM69). To continue use this an older version of RFM69 library is necessary.
Also, [RFM69 library](https://github.com/LowPowerLab/RFM69) need be tweaked to use [SPIFlashA](https://github.com/rrobinet/SPIFlashA) instead of [SPIFlash](https://github.com/LowPowerLab/SPIFlash).

# Anarduino Wireless Programming library
=======================================
WirelessAnarduinoHEX69 

 * Library for facilitating wireless programming using RFM69 transceivers (get libraries here: [RFM12B](https://github.com/LowPowerLab/RFM12B) and [RFM69](https://github.com/LowPowerLab/RFM69))
 * and the SPI Flash memory library for anarduino miniwireless (get library here: [SPIFlashA](https://github.com/rrobinet/SPIFlashA))
 * DEPENDS ON the two libraries mentioned above

### License

This library is free software; you can redistribute it and/or modify it under the terms of either the GNU General Public License version 2 or the GNU Lesser General Public License version 2.1, both as published by the Free Software Foundation.

This library is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU Lesser General Public License for more details
