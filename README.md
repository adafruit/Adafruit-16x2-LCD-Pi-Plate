# PCB files for Adafruit 16x2 LCD Pi Plate for Raspberry Pi

<a href="http://www.adafruit.com/products/1110"><img src="assets/image.jpg?raw=true" width="500px"><br/>Click here to purchase one from the Adafruit shop</a>

* https://www.adafruit.com/product/1110
* https://www.adafruit.com/product/1115
* http://www.adafruit.com/products/1109

This new Adafruit Pi Plate makes it easy to use a blue and white 16x2 Character LCD. [We really like the 16x2 Character LCDs we stock in the shop](http://www.adafruit.com/products/181). Unfortunately, these LCDs do require quite a few digital pins, 6 to control the LCD and then another 1 to control the backlight for a total of 7 pins. That's nearly all the GPIO available on a Pi!

With this in mind, we wanted to make it easier for people to get these LCD into their projects so we devised a Pi plate that lets you control __a 16x2 Character LCD, up to 3 backlight pins AND 5 keypad pins using only the two I2C pins on the R-Pi!__ The best part is you don't really lose those two pins either, since you can stick i2c-based sensors, RTCs, etc and have them share the I2C bus. This is a super slick way to add a display without all the wiring hassle.

__New, we've updated this Pi plate so the buttons on on the right side, which makes it a little more mechanically stable__

This pi plate is perfect for when you want to build a stand-alone project with its own user interface. The 4 directional buttons plus select button allows basic control without having to attach a bulky computer.

The plate is designed for both Revision 1 and Revision 2 Raspberry Pi's. It uses the I2C (SDA/SCL) pins. We have a special xtra-tall 26-pin header so the plate sits above the USB and Ethernet jacks. __For Pi Model B+ and Pi 2,__ the resistors sit right above the new set of USB ports. To keep them from shorting against the metal, a piece of electrical tape must be placed onto the USB ports.

__This product comes as a kit!__ Included is a high quality PCB and all the components (buttons, header etc). __A 16x2 Character blue&white monochrome LCD is included!__ Assembly is easy, even if you've never soldered before and the kit can be completed in 30 minutes. [Check the product tutorial page for assembly instructions before purchasing](http://learn.adafruit.com/adafruit-16x2-character-lcd-plus-keypad-for-raspberry-pi). You may get a 2-row or 1-row connector LCD, either will work fine.

[We also have some handy Python code to help you easily talk to the LCD and buttons](http://learn.adafruit.com/adafruit-16x2-character-lcd-plus-keypad-for-raspberry-pi).
You can also easily query the 5 keypad buttons to get input through the library, so you get extra buttons without using any more pins. The buttons are automatically de-bounced inside the library.

At this time, the code and plate can control the white backlight on or off. There is no support for PWM control of the backlight at this time, so if you need to have more granular control of the backlight, this plate can't do that (the I2C expander does not have PWM output).


## License

Adafruit invests time and resources providing this open source design, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Designed by Limor Fried/Ladyada for Adafruit Industries.
Released under Creative Commons - Attribution/Share-Alike
All text above must be included in any redistribution
