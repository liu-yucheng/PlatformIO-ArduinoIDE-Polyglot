# PlatformIO-ArduinoIDE-Polyglot

A polyglot project that can be used as either a PlatformIO or an ArduinoIDE project.
Tested on MCU ESP8266 Board WeMos D1 R1.
In theory, this should work on all boards with MCU ESP8266 or ESP32.
Project code behaves the same as the Blink Arduino IDE Example code.

# Usage

## Usage as a PlatformIO Project

- Open the project root folder with [PlatformIO for VSCode](https://platformio.org/platformio-ide).
- Install the following **platforms**.
```
Espressif 8266
Espressif 32
```
- ~~Install the following **libraries**.~~
(Add your project dependencies below.)
```
```
- Compile the firmware.
- Flash the compiled firmware to any board with MCU ESP8266 or ESP32.

## Usage as an Arduino Project

- Open `./src/src.ino` with [`Arduino IDE`](https://www.arduino.cc/en/software).
- Add the following **additional board manager URLs**.
```
http://arduino.esp8266.com/stable/package_esp8266com_index.json,
https://espressif.github.io/arduino-esp32/package_esp32_index.json
```
- Install the following **boards**.
```
Arduino AVR Boards,
Arduino ESP32 Boards,
esp32,
esp8266
```
- ~~Install the following **libraries**.~~
(Add your project dependencies below.)
```
```
- Compile the project files.
- Flash the compiled project files to any board with MCU ESP8266 or ESP32.

# Copyright

```
PlatformIO-ArduinoIDE-Polyglot.
Copyright (C) 2026 Yucheng Liu. GNU AGPL 3.0 license.
GNU AGPL 3.0 License: https://www.gnu.org/licenses/agpl-3.0.txt .
```
