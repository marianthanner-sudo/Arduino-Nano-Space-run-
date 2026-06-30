# Arduino-Nano-Space-run-
Small Project with Arduino Nano and an ST7789 OLED display, with which you can play Space Run, a small game I coded where you dodge meteors with a space shuttle. Pretty good for beginners. 

the new version uses 2 buttons left and right the game has 3 game modes one is normal dodge game second is like a line passing game and thrird is a simon says have fun :))

Materials:

-Arduino Nano 
-3x touch pins
-1.54 TFT oled display ST7789
-5x 2k resistors 
-Additional battery 

Pin layout:

Display:
gnd - gnd
vcc - 3v3
scl - D13 2k Resistor!!!
sda - D11 2k Resistor!!!
rst - D8 2k Resistor!!!
dc - D9 2k Resistor!!!
cs - D10 2k Resistor!!!
bl - 3v3 

left touch:
gnd - gnd
vcc - 3v3 
out - A0


right touch:
gnd - gnd
vcc - 3v3 
out - A1

Additional battery:
Plus - Vin (on the arduino)
Minus - gnd (on the arduino)

Have fun with the game !!!!!!
