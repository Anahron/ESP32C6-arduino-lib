
ESP32C6 Arduino CAN Library (Validation Disabled)

This repository contains a modified version of the standard ESP32-C6 Arduino libraries.

Overview

This is based on the official ESP32 Arduino core libraries, but with internal validation checks disabled to allow faster initialization
and quicker startup time

What Was Changed
CONFIG_BOOTLOADER_SKIP_VALIDATE_IN_DEEP_SLEEP=y
CONFIG_BOOTLOADER_SKIP_VALIDATE_ON_POWER_ON=y

This is useful for automotive projects

Installation
use it as a replacement for the default ESP32-C6 library:
[ARDUINO_LIB]\hardware\espressif\esp32\tools\esp32-arduino-libs\esp32c6

Disclaimer
This is not an official Espressif release.
Use at your own risk.
