<h1>3D printed RC Articulated Dump Truck</h1>
<img src="https://github.com/swholmstead/DumpTruck/blob/main/docs/IMG_3389.JPEG" alt="Skidsteer" width=600 height=400>

<h2>Contents</h2>
* Bill of Materials<br>
* Schematic and Printed Circuit Board (PCB)<br>
* Assembly Instructions<br>
* [Arduino IDE](docs/arduino.md)<br>

<h2>Arduino IDE</h2>

Download IDE from https://www.arduino.cc/en/software

Under File > Preferences, set Additional boards manager URLs to https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
https://raw.githubusercontent.com/ricardoquesada/esp32-arduino-lib-builder/master/bluepad32_files/package_esp32_bluepad32_index.json

Add libraries:
* ESP32Servo by Kevin Harrington

Under Tools > Board > Board Manager, add these boards
* esp32_bluepad32 by Richard Quesada

Under Tools > Board, select esp32_bluepad32 > ESP 32 Dev Module

<h2>Schematic and Gerber Files</h2>
Gerber files can be used to manufacture printed circuit board by uploading to a site like https://jlcpcb.com/
<img src="https://github.com/swholmstead/DumpTruck/blob/main/docs/schematic.png" alt="Schematic" width=600>
<img src="https://github.com/swholmstead/DumpTruck/blob/main/docs/PCB.png" alt="PCB" width=400>
