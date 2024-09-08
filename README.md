# samd21g-midi-tool
[kicad](https://www.kicad.org/) design files for a general purpose midi dev board based on Arduino MKRZero 

* [samdg21](https://www.microchip.com/en-us/product/atsamd21g18) arm cortex m0 microcontroller
* DIN-5 midi input and output
* st7735 display (128x128 16bit)
* [PCF8523T](https://www.nxp.com/part/PCF8523T) realtime clock RTC
* socket for micro-SD card
* status LED
* SWD connection for programming
* PJ-320A connector for 2 foot-switches
* 5V POWER via USB
* 3V3 regulator
* 4-pin socket for neopixel strip
* Status LED

<img src="docs/top-left.JPG" alt="drawing" width="400"/>

## Kicad plugins
 * [JLCPCB](https://github.com/Bouni/kicad-jlcpcb-tools)
 * [Freerouting](https://github.com/freerouting/freerouting)

## sources / credits:
  * schematics and pcb design based on [MKRZERO Arduino](https://docs.arduino.cc/hardware/mkr-zero/)   
  * 3d models:
    * [PJ320A PJ320D 3.5mm JACK](https://grabcad.com/library/pj320a-pj320d-3-5mm-jack-1)
    * [SMD CR1220 Battery case](https://grabcad.com/library/smd-cr1220-battery-case-1)
  * footprints
    * [PJ-320A](https://github.com/nathanhborger/PJ-320A_KiCad_Library)

## images
<img src="docs/top.png" alt="drawing" width="400"/>
<img src="docs/bottom.png" alt="drawing" width="400"/>

![tech-assembly](docs/tech-assembly.png)

![tech-assembly-with-enclosure](docs/tech-assembly-with-enclosure.png)
