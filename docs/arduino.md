<h2>Arduino IDE</h2>

Download IDE from https://www.arduino.cc/en/software

Under File > Preferences, set Additional boards manager URLs to https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json,https://raw.githubusercontent.com/ricardoquesada/esp32-arduino-lib-builder/master/bluepad32_files/package_esp32_bluepad32_index.json

Add libraries:
 * ESP32Servo by Kevin Harrington

Under Tools > Board > Board Manager, add these boards
* esp32_bluepad32 by Richard Quesada

Under Tools > Board, select esp32_bluepad32 > ESP 32 Dev Module

Connect ESP32 Development Kit with USB cable
Under Tools > Port, select COM port used

Open DumpTruck_Bluepad.ino file and click right arrow on top tool bar to download code to ESP32

<h2>Controls</h2>

* Left joystick y-axis controls speed and x-axis controls steering.
* Right joystick y-axis controls dump bed.
* "A" button turns lights on/off.
* "B" button executes "wiggle" function, moving motors and flashing lights.  If you have more than one vehicle, the button helps you
identify which vehicle is paired with this controller.
* Left bumper (L1 button) puts drive train in "low gear".  This makes it easier to attach a trailer or perform more precise movements.
