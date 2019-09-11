## Adafruit PCT2075 Temperature Sensor PCB

<a href="http://www.adafruit.com/products/4369"><img src="assets/4369.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit PCT2075 Temperature Sensor. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/products/4369

### Description

The PCT2075 by NXP is a pin compatible drop in replacement for a very common I2C temperature sensor, the LM75. Compared to the LM75 however, the 11-bit ADC in the PCT2075 provides more precise measurements when compared to the LM75's 9-bit ADC. Additionally because the PCT2075 allows the address pins to work in three states (high, low, floating), you can have 27 PCT2075s on the same bus as opposed to only 8 for the LM75. Now you can finally measure the temperature the individual temperatures of the tentacles of three octopuses instead of just one!

Otherwise the two sensors are the same. The PCT2075 will report temperature and allow you to a set a high temperature threshold that the sensor will compare to the current temperature and raise an alert when the current temperature exceeds the threshold. There are also a few (metaphorical) knobs to twist to change the alerting and measurement behavior.

As with all Adafruit breakouts, we've done the work to make this handy temperature helper super easy to use. We've put it on a breakout board with the required support circuitry and connectors to make it easy to work with, and is now a trend we've added  [SparkFun Qwiic](https://www.sparkfun.com/qwiic) compatible [STEMMA QT](https://learn.adafruit.com/introducing-adafruit-stemma-qt) JST SH connectors that allow you to get going without needing to solder. Just use a [STEMMA QT adapter cable](https://www.adafruit.com/product/4209), plug it into your favorite micro or Blinka supported SBC and you're ready to rock!

"OK" you say "connections are one thing but how do I tell it what to do? (Not much of a) Surprise! We've written libraries for Arduino and CircuitPython with examples that make it super easy to integrate the PCT2075 with your project.

The PCT2075 is a handy and inexpensive temperature sensor that does one thing well. Try adding on to your project and have it keep an eye on the temperature and let you know when things get hot.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Bryan Siepert for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
