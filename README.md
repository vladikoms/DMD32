# DMD32
A library for driving the 512 pixel dot matrix LED display, a 32 x 16 layout using ESP32 Lite V1.0.0 https://aliexpress.ru/item/33009178296.html.

This library is a fork of the original one https://github.com/Qudor-Engineer/DMD32.

The connection between ESP32 and display configure in DMD32.h file:

HUB12  ESP32
OE      D19
A       D16
B       D17
CLK     D18
LAT     D4
DR      D23

Use Arduino core for the esp32 by Espressif Systems v.2.0.2 or earlier.
