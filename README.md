# Arduino analog clock
Displayes an analog clock on an lcd screen, 

## Reqiurements:
- Arduino UNO
- LCD Screen (SSD1306 I2C 128x64 pixels)
- ds3231 clock module
- Piezo
- Button
- Resistor

## Wiring:
1. Connect the screen and clock module to sda, scl, vcc and gnd
2. Connect the Piezo to gnd and pin 6 on the arduino
3. connect the button to vcc and pin 7
4. connect the resistor between the negative side of the button and gnd
