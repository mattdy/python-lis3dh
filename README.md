# **DEPRECATION WARNING**
Adafruit has deprecated their [Adafruit_Python_GPIO library](https://github.com/adafruit/Adafruit_Python_GPIO) in favour of [blinka](https://github.com/adafruit/Adafruit_Blinka), which allows you to use their full-fledged CircuitPython code for the sensor. This can be found here: https://github.com/adafruit/Adafruit_CircuitPython_LIS3DH.

The library in this repository will still function under Python 2, however [Python 2 has reached end-of-life](https://www.python.org/doc/sunset-python-2/) and you should therefore move to using the above libraries with Python 3.

Because of this, this repository will be archived and no further updates will be made. My thanks to everyone who has contributed to it in the past.

# python-lis3dh
Python library for using a [LIS3DH triple-axis accelerometer](https://www.adafruit.com/products/2809) on a Raspberry Pi

This is not a complete implementation of all the features of the LIS3DH - if you can help add more functionality then please contribute!

## Requirements
Requires the Adafruit_Python_GPIO library which can be found at https://github.com/adafruit/Adafruit_Python_GPIO

## Useful reading
 * https://www.adafruit.com/product/2809
 * https://www.adafruit.com/datasheets/LIS3DH.pdf
 * https://github.com/adafruit/Adafruit_LIS3DH/blob/master/Adafruit_LIS3DH.cpp
 * https://github.com/adafruit/Adafruit_LIS3DH/blob/master/Adafruit_LIS3DH.h
 * https://github.com/adafruit/Adafruit_Python_GPIO

## Credits
 * [Matt Dyson](http://mattdyson.org) - Original implementation
 * [Mal Smalley](https://github.com/MalSmalley) - Implementation of 'click' functionality
 * [Tunniel Holzfigure](https://github.com/holzfigure) - Adaptation for new Adafruit library
