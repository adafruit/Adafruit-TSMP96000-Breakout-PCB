## Adafruit TSMP96000 "Code Learning" Infrared IR Receiver Breakout - STEMMA JST PH 2mm PCB

<a href="http://www.adafruit.com/products/5970"><img src="assets/5970.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit TSMP96000 "Code Learning" Infrared IR Receiver Breakout - STEMMA JST PH 2mm. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5970

### Description

For classic 38KHz infrared remote signal reading, we've got a lovely STEMMA IR Receiver. But if you want to read infrared signals from remotes with different carrier signals, especially when you don't know the frequency, this Adafruit TSMP96000 "Code Learning" Infrared IR Receiver Breakout has the ability to detect IR signals from 20 to 60KHz and provide the carrier signal for analysis. This is used for "code learning" situations where you want your device to work with any IR remote control.

Usage is simple: Power the board by connecting V+ and ground to 3~5VDC, point a 20~60KHz IR remote control at the sensors, and press some buttons. The modulated IR signal, with the carrier signal intact, is piped out the Signal pin into your microcontroller which will then need to decode it. To make usage really easy, we have a green 'power good' LED and a red 'signal' LED. When IR remote signals are read by the onboard sensors, the red LED will blink to let you know.

This board will work nicely for advanced IR remote receiving projects, because you don't get the demodulated output it's not good for most IR decoding firmware - make sure you've got code specifically designed for "code learning"! With mounting holes and a cable, it's easy to mount in enclosures and on devices. Using a 2mm pitch STEMMA JST PH cable with headers or alligator clips on the end, you can easily wire this board without any soldering.

Each STEMMA board is a fully assembled and tested PCB, but no cable. No soldering is required to use it, but you will need to pick up a 2mm pitch, 3-pin STEMMA JST PH cable. Alternatively, if you do want to solder, there's a 0.1" spaced header for power/ground/signal.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
