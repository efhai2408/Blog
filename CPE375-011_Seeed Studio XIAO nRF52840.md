date: 2024-02-23
time: 05:19
---
# Introduction



# About Seeed Studio XIAO nRF52840 (Sense)


Seeed Studio XIAO nRF52840 (Sense) is a microcontroller board embedded with the nrf52840 SoC, developed for IoT and machine learning projects. It is compatible with USB-C 2.0 and Bluetooth 5.0. 
this board is one of the smallest IOT board in the market, it has the size of 20 x 17.5mm which is smaller compared to 10 Baht coin. 

It has 14 pins in total, which are 11 PWM and 6 analog pins; 
Can be programmed by many languages; Arduino, MicroPython, CircuitPython


I guess many of us here are somewhat interested in AI and machine learning techs. This board was designed specifically for those tasks and IOT applications. 
For IOT applications, this board embedded with bluetooth module, and for ML&AI application, this board embedded with 2 useful sensor for those kind of tasks, the first one is Pulse Density Modulation (PDM) Digital Microphone that is useful in recording or voice recognition tasks, the second one is LSM6DS3TR-C, an 6-DOF inertial measurement unit (IMU) sensor that is helpful in gesture recognition tasks.

This device has a reset button on-board, which makes it easy to enter bootloader mode. 

# Some interesting and Remarkable applications
- Bluetooth Robot
	- [here are some examples](https://www.seeedstudio.com/blog/2023/12/08/robotic-designs-based-on-xiao-series/)
  	- [![Watch the video](https://img.youtube.com/vi/ZoYiQNPuftg/maxresdefault.jpg)](https://youtu.be/ZoYiQNPuftg)
- Smart watch 
	- this board embedded with nRF52840 Chip, a very compact, yet powerful and high-spec board with 32-Bit ARM cpu. with it’s very small and compact size, Bluetooth module and many variety of sensor modules embedded, NFC for payment included, It has  It is very suitable for diy smartwatch and other kind of wearable technology projects. There is an existing round OLED display designed specifically for this board from Seeed studio themselves.
- Keyboard and mouse 
	- with the powerful nRF52840 Chip, there are already some low-latency gaming product used this chip in the market, and the document of this chipset also provided the examples of keyboard and mouse applications. This board is suitable for making diy bluetooth keyboard and mouse
# Limitation
Number of pins
With the number of pins (14 pins) is less than many boards with similar applications, e.g. Arduino Nano board has 22 pins and nice!nano board has 23 pins, this board might not be the best option in very complex tasks that require many pins.
# References

https://wiki.seeedstudio.com/XIAO_BLE/ 

https://youtu.be/vrcPGeYinVQ?si=ZH9rXFYduLzatEcQ
