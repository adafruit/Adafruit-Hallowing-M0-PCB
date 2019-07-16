## Adafruit HalloWing M0 Express PCB

<a href="http://www.adafruit.com/products/3900"><img src="assets/3900.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit HalloWing M0 Express. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/3900

### Description
[This is Hallowing..this is Hallowing... Hallowing! Hallowing!](https://www.youtube.com/watch?v=kGiYxCUAhks&t=39s)
Are you the kind of person who doesn't like taking down the skeletons and spiders until after January? Well, we've got the development board for you. This is electronics at its most spooky! The **Adafruit HalloWing** is a skull-shaped ATSAMD21 board with a ton of extras built in to make for an adorable wearable, badge, development kit, or the engine for your next cosplay or prop.

On the front is a cute **1.44" sized 128x128** full color TFT. Our default example code has our spooky eye demo running but you can use it for anything you like to display in glorious color.

There's also 4 fang-teeth below the display, these are analog/capacitive touch inputs with big alligator-clip holes.

On the reverse is a smorgasbord of electronic goodies:

 * **ATSAMD21G18** @ 48MHz with 3.3V logic/power - 256KB of FLASH + 32KB of RAM
 * **8 MB of SPI Flash** for storing images, sounds, animations, whatever!
 * **3-axis accelerometer** (motion sensor)
 * **Light sensor**, reverse-mount so that it points out the front
 * **Mono Class-D speaker driver** for 4-8 ohm speakers, up to 2 Watts, with mini volume pot
 * LiPoly battery port with built in recharging capability
 * USB port for battery charging, programming and debugging
 * Two female header strips with Feather-compatible pinout so you can plug any FeatherWings in
 * JST ports for Neopixels, sensor input, and I2C (you can fit I2C Grove connectors in here)
 * 3.3V regulator with 500mA peak current output
 * Reset button
 * On-Off switch

**OK so technically it's more like a really tricked-out Feather M0 Express than a Wing but we simply could not resist the Hallowing pun.**

Right now you can use the Hallowing similarly Feather M0 Express, it's got the same chip although the pins have been rearranged. We've got both Arduino and CircuitPython build support for it so you can pick your favorite development language! The extra 8 MB of SPI Flash is great for sound effects projects where you want to play up to 3 minutes of WAV files.

On each side of the Hallowing are JST-PH plugs for connecting external devices. The 3-pin JSTs connect to analog pins on the SAMD21, so you can use them for analog inputs. We label one for Neopixel and one for Sensors since we think most people will have one of each. The 4-pin JST connector connects to the I2C port and you can fit Grove connectors in it for additional hardware support.

**Does not come with a Lipoly battery!** [We recommend our 350mAh](https://www.adafruit.com/product/2750) or [500mAh batteries](https://www.adafruit.com/product/1578) but any 3.7/4.2V Adafruit Lipoly will do the trick.

Comes fully assembled and ready to be your spooky friend. We install the UF2 bootloader on it so updating code and converting it to CircuitPython is easy. [Check out the Adafruit Learn guide for software, libraries, example code, schematics, datasheets and more!](https://learn.adafruit.com/adafruit-hallowing)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
