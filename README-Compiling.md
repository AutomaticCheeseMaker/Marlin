# How to Compile

Install Arduino 1.8.13  (https://www.arduino.cc/en/software)

Select Arduino Mega as Board, ATMega2560 as Processor

Install the following Arduino Libraries (via Sketch -> Include Libaries -> Manage Libraries)
- OneWire 2.3.5
- DallasTemperature 3.9.0

After uploading you should probably clear EEPROM by opening Serial Monitor (with Baud 9600) and issueing:
```
M502
M500
```
