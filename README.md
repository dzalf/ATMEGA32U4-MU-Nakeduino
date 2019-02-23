# ATMEGA32U4-MU-Nakeduino
A standalone breakout board for the Arduino Leonardo or [Pro Micro](https://shop.pimoroni.com/products/pro-micro-5v-16mhz?variant=7487693313&gclid=Cj0KCQiA-8PjBRCWARIsADc18TK3GjFquPD7BkRoYZJYw_GjSvD04rzGwPerEhrzXqwTqM_zomNSwFMaAuS2EALw_wcB)

**WELCOME EVERYONE!** :wave:

This is the repository for the Nakeduino Leonardo/Pro Micro based on the [ATMEGA32U4-MU](http://ww1.microchip.com/downloads/en/devicedoc/atmel-7766-8-bit-avr-atmega16u4-32u4_datasheet.pdf).

It is a breakout board designed for those who are looking for a solution for prototyping standalone Arduinos. With this bare board you will have full control of your design before implementing your own standalone Arduino in your projects.

I believe it is important  when designing embedded systems because usually designers/hobbysts (including myself) take for granted many details regarding the functional sections of the Arduino. For example:

a. Reset circuitry, you can test your own RST design
b. ICSP connections, to make sure that the program can be loaded in case you don't plan to use the USB onboard (in that case you could use the ATMEGA328P for which I will upload another breakout board design :wink:)
c. clock signal generators, allowing you to test the best crystal and capacitors quality or even test your resonator of choice,
d. USB connections,
e. Approriate power supplies for the MCU
f. ....many other advantages

In addition, with this board you will have access to all of those pins that are not routed on those micro boards like the Pro Micro. For example: in D17 is assigned only to the Rx LED and perhaps your project needs to use CS from the SPI Port being that D17 also corresponds to that pin.

The pinout is based on the schematic symbol from [KiCAD](http://kicad-pcb.org/), as follows :eyes:

![alt txt](https://github.com/dzalf/ATMEGA32U4-MU-Nakeduino/blob/master/ATMEGA32U4-MU%20Nakeduino-schematic.png)
![alt txt](https://github.com/dzalf/ATMEGA32U4-MU-Nakeduino/blob/master/ATMEGA32U4-MU%20Nakeduino.png)

Please feel free to leave your comments and in case you want to modify and adapt the board to your needs fork the repo and don't forget to give me some credit for it :pray:

Cheers :beer:

dzalf :sunglasses:


**#TODO**

1. Upload examples of the applicability of this boards (pictures)
