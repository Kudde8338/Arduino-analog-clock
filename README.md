# Arduino analog clock
Displayes an analog clock on an lcd screen, and also posseses alarm capabilities.

## Reqiurements:
- Arduino UNO
- LCD Screen (SSD1306 I2C 128x64 pixels)
- ds3231 clock module
- Piezo
- Button
- Resistor

## Wiring:
1. Connect the screen and clock module to sda, scl, vcc and gnd.
2. Connect the Piezo to gnd and pin 6 on the arduino.
3. connect the button to vcc and pin 7.
4. connect the resistor between the negative side of the button and gnd.

## Setting an alarm:
1. Press the button once to open the alarm menu.
2. press the button to increment the hours.
3. long press the button to switch to minutes.
4. press the button to increment the minutes.
5. long press the button to save.
