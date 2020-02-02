# APA102 Led tester - test your led strip

This is very simple project to test APA102 led strip functionality before you use it in production. To test functionality I'm using small and cheap [ATINNY85 mini arduino board](https://www.amazon.com/ATTINY85-Mini-Development-Board-Arduino/dp/B010B1SR5W).

How to use this board with Arduino IDE you can find for example here: https://digistump.com/wiki/digispark/tutorials/connecting

Wiring is very simple according to image below:

Wire color | Board pin | APA102 pin
---------- | --------- | ----------
blue       | GND (-)   | GND
black      | 5V (+)    | 5V
green      | P2        | CI
red        | P0        | DI

![APA102 + ATINNY85](https://raw.githubusercontent.com/martinbilek/apa102-led-tester/master/img/img.jpg)

To run the code, just upload project to the board. Before upload you need to install [FastLED](https://github.com/FastLED/FastLED) library to Arduino IDE.
