# RCM-Hardware-Nibble
v1.8

Half a [BYTE](https://github.com/RCMgames/RCM-Hardware-BYTE)

* 1.08 by 1.12 inches, 27.432 by 28.448 millimeters
* 4 motors
* 4 servos
* 2 additional GPIO pins
* built-in [IMU](https://github.com/RCMgames/useful-code/blob/main/sensors/IMUs/ICM20948/ICM20948_helper.h)
* battery monitoring
* I2C connector on QT PY
* runs on 3-11 volts

program with [RCMv2](https://github.com/RCMgames/RCMv2)

### Tested with the following types of ESP32 QT Py:
| Type of QT Py | PlatformIO name | link to Adafruit |
| ------ | -------- | -------- |
| S3 with 2MB PSRAM |  adafruit_qtpy_esp32s3_n4r2   |  https://www.adafruit.com/product/5700   |
| S3 with 8Mb Flash |  adafruit_qtpy_esp32s3_nopsram   |  https://www.adafruit.com/product/5426   |
| S2 |  adafruit_qtpy_esp32s2   |  https://www.adafruit.com/product/5325  |

Look here for how to program it: https://github.com/RCMgames/RCMv2

Look here for more information and examples of robots: https://github.com/rcmgames

Want slightly larger and 8 motors and 8 servos? Look at the [BYTE](https://github.com/rcmgames/RCM-Hardware-BYTE)

## Options for purchasing

* [PCBWay link](https://www.pcbway.com/project/shareproject/RCMhardwareNibble_v1_8_dbf51cb4.html) (PCBWay will give me a commission without increasing the price for you). (approximately $110 for 2 boards and manufacturing took a month).
* send the gerbers, bill of materials, and ComponentPlacement files (in /PCBproduction-RCM-Nibble) to a PCB manufacturer of your choice (details you may be asked for: min hole 0.25mm, min track/spacing 5/5mil, thickness 1.0mm, 1 oz Cu outer 1.5 oz Cu inner, tell them to not solder the icm20948's exposed pad)

## Components
Solder by hand to complete the assembly of your boards.
| part | links | quantity | notes |
| ----- | ----- | ----- | ----- |
| RCM Nibble circuit board | [options for purchasing](https://github.com/RCMgames/RCM-Hardware-Nibble/tree/main#options-for-purchasing) | 1 | |
| ESP32 QT Py | [compatible QT Py](https://github.com/RCMgames/RCM-Hardware-Nibble/tree/main#tested-with-the-following-types-of-esp32-qt-py) | 1 | |
| 2x4 female header pins | [this](https://www.digikey.com/en/products/detail/sullins-connector-solutions/PPPC042LFBN-RC/810244) or 2 strips of 4 | 1 | for motors |
| 7 female header pins | | 2 | for QT Py |
| 3 male header pins | | 4 | for servos |
| 2 male header pins | | 2 | for extra GPIO pins |
| battery wires | JST RCY OR 9V battery snap | 1 | [Amazon JST RCY](https://www.amazon.com/dp/B00Z04QFN2/) |
| servo buck boost 5v 2A | [Pololu](https://www.pololu.com/product/4085) | 0 or 1 | if you want to supply voltages above or below what servos can accept (supplies other than 5AAs) |

![photos](https://github.com/RCMgames/RCM-Hardware-Nibble/blob/5cc9267ceca6876412c50ad4705f115df2f20e71/photos/P1040798.JPG)
![photos](https://github.com/RCMgames/RCM-Hardware-Nibble/blob/5cc9267ceca6876412c50ad4705f115df2f20e71/photos/P1040800.JPG)

## Acknowledgements
* I would like to thank [PCBWay](https://www.pcbway.com/) for sponsoring prototyping runs of this project. PCBWay produces very nice boards, supports open source hardware, and gave me great support as I worked on this project. Special thanks to Liam!
