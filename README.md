# SMARTREXE_displayDriver
Display Driver for the ST7586 Controller used in the Smart Response XE

Whoo, my first github upload!

So, this is a driver for pixel-precise writing onto the display.
It also features additional functions to create a temporary buffer on the microcontroller,
to bypass the problem hat the display controller cannot be read with a SPI interface (as it is with the Smart Resp... XE).
