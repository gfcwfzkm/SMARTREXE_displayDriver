# SMARTREXE_displayDriver
Display Driver for the ST7586 Controller used in the Smart Response XE

Whoo, my first github upload!

So, this is a driver for pixel-precise writing onto the display.
It also features additional functions to create a temporary buffer on the microcontroller,
to bypass the problem that the display controller cannot be read back with a SPI interface.
