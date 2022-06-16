# PetPull32

![Image alt](https://github.com/3DThing/petpull32/blob/main/Hardware/PCB_TOP.svg) ![Image alt](https://github.com/3DThing/petpull32/blob/main/Hardware/PCB_DOWN.svg)

This board based on ESP32 WROOM 4-16mb with support wifi and bluetooth. Designed for the production of filament for 3D printing, with a diameter of 1.75mm.

The board supports:
1. WiFi and Bluetooth.
2. Two NTC 100kΩ thermistors
3. K-type thermocouple through the MAX6675ISA chip.
4. Heater 40-100 watts.
5. Stepper motor driver A4988 or similar.


The control takes place through the LCD display via the I2C interface as well as through the encoder KY-040.
To warn about critical errors, overheating, etc., a buzzer is connected to GPIO17.
