<h2>Arduino IDE</h2>

Download IDE from https://www.arduino.cc/en/software

Under File > Preferences, set Additional boards manager URLs to https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
https://raw.githubusercontent.com/ricardoquesada/esp32-arduino-lib-builder/master/bluepad32_files/package_esp32_bluepad32_index.json

Add libraries:
 * ESP32Servo by Kevin Harrington

Under Tools > Board > Board Manager, add these boards
* esp32_bluepad32 by Richard Quesada

Under Tools > Board, select esp32_bluepad32 > ESP 32 Dev Module

Connect ESP32 Development Kit with USB cable
Under Tools > Port, select COM port used

Open DumpTruck_Bluepad.ino file and click right arrow on top tool bar to download code to ESP32
