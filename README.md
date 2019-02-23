# ATMEGA32U4-MU-Nakeduino
A standalone breakout board version of the Arduino Leonardo or Pro Micro

**WELCOME EVERYONE!** :wave:

This is the repository for the Nakeduino Leonardo/Pro Micro based on the ATMEGA32U4-MU.

It is a breakout board designed for those who are looking for a solution for prototyping standalone Arduinos. With this bare board you will have full control of your design previous implementing your own standalone arduino in your projects.

I believe it is important  when designing embedded systems because usually designers/hobbysts (including myself) take for granted many details regarding the functional sections of the Arduino. For example:

a. Reset circuitry, in order to test your own RST design
b. ICSP connections, to make sure that the program can be loaded in case you don't plan to use the USB onboard (in that case you could use the ATMEGA328P for which I will upload another breakout board design :wink:)
c. clock signal generators, allowing you to test the best crystal and capacitors quality or even test your resonator of choice,
d. 

In addition, with this board you will have access to all of those pins not routed on mini or micro boards like the Pro Micro. For example: in D17 is assigned only to the Rx LED and perhaps your project needs to use CS from the SPI Port being that D17 also corresponds to that pin.

The pinout is based on the schematic symbol from KiCAD, as follows :eyes:

![alt txt](https://github.com/dzalf/ATMEGA32U4-MU-Nakeduino/blob/master/ATMEGA32U4-MU%20Nakeduino-schematic.png)
![alt txt](https://github.com/dzalf/ATMEGA32U4-MU-Nakeduino/blob/master/ATMEGA32U4-MU%20Nakeduino.png)

Please feel free to leave your comments and in case you want to modify and adapt the board to your needs fork the repo and don't forget to give me some credit for it :pray:

Cheers :beer:

dzalf :sunglasses:
