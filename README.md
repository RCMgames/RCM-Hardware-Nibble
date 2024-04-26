# RCM-Hardware-Nibble
v1.5

UNDER DEVELOPMENT

Half a [BYTE](https://github.com/RCMgames/RCM-Hardware-BYTE)

* about 1x1 inches
* 4 motors
* 4 servos
* 2 additional GPIO pins
* built-in [IMU](https://github.com/RCMgames/useful-code/tree/main/ICM20948)
* battery monitoring
* I2C connector on QT PY
* runs on 3-11 volts

program with [RCMv2](https://github.com/RCMgames/RCMv2)


Tested with the following types of ESP32 QT Py:
| Type of Qt Py | PlatformIO name | link to Adafruit |
| ------ | -------- | -------- |
| S3 with 2MB PSRAM |  adafruit_qtpy_esp32s3_n4r2   |  https://www.adafruit.com/product/5700   |
| S3 with 8Mb Flash |  adafruit_qtpy_esp32s3_nopsram   |  https://www.adafruit.com/product/5426   |
| S2 |  adafruit_qtpy_esp32s2   |  https://www.adafruit.com/product/5325  |
| C3 | adafruit_qtpy_esp32c3  | https://www.adafruit.com/product/5405 |

## Options for purchasing

* PCBWay link (coming soon, after testing is complete) (PCBWay will give me a commission without increasing the price for you). (approximately $110 for 2 boards and manufacturing took a month).
* send the gerbers, bill of materials, and ComponentPlacement files to a PCB manufacturer of your choice (details you may be asked for: min hole 0.3mm, min track/spacing 5/5mil, thickness 1.0mm, 1 oz Cu outer 1.5 oz Cu inner)

![screenshot of 3D model](https://github.com/RCMgames/RCM-Hardware-Nibble/blob/af1beba9ec100e7f6b639da1eef72971af2435cc/CAD%20renders-RCM-Nibble-v1.5/render1.jpg)
