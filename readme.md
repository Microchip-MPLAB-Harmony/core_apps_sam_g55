﻿---
title: Harmony 3 driver and system service application examples for SAM G55 family
nav_order: 1
has_children: true
has_toc: false
---
[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# Harmony 3 driver and system service application examples for SAM G55 family

MPLAB® Harmony 3 is an extension of the MPLAB® ecosystem for creating embedded firmware solutions for Microchip 32-bit SAM and PIC® microcontroller and microprocessor devices.  Refer to the following links for more information.

- [Microchip 32-bit MCUs](https://www.microchip.com/design-centers/32-bit)
- [Microchip 32-bit MPUs](https://www.microchip.com/design-centers/32-bit-mpus)
- [Microchip MPLAB X IDE](https://www.microchip.com/mplab/mplab-x-ide)
- [Microchip MPLAB® Harmony](https://www.microchip.com/mplab/mplab-harmony)
- [Microchip MPLAB® Harmony Pages](https://microchip-mplab-harmony.github.io/)

This repository contains the MPLAB® Harmony 3 driver and system service application examples for SAM G55 family

- [Release Notes](release_notes.md)
- [MPLAB® Harmony License](mplab_harmony_license.md)

To clone or download these applications from Github, go to the [main page of this repository](https://github.com/Microchip-MPLAB-Harmony/core_apps_sam_g55) and then click **Clone** button to clone this repository or download as zip file.
This content can also be downloaded using content manager by following these [instructions](https://github.com/Microchip-MPLAB-Harmony/contentmanager/wiki).

## Contents Summary

| Folder     | Description                             |
| ---        | ---                                     |
| apps       | Contains driver and system service example applications |
| docs       | Contains documentation in html format for offline viewing (to be used only after cloning this repository onto a local machine). Use [github pages](https://microchip-mplab-harmony.github.io/core_apps_sam_g55/) of this repository for viewing it online. |

## Code Examples

The following applications are provided to demonstrate the typical or interesting usage models of one or more peripheral libraries.

| Name | Description |
| ---- | ----------- |
| [I2C driver asynchronous - I2C EEPROM](apps/driver/i2c/async/i2c_eeprom/readme.md) | This example application demonstrates how to use the I2C driver in asynchronous mode to perform read/write operations on an EEPROM |
| [I2C driver asynchronous - I2C multi slave](apps/driver/i2c/async/i2c_multi_slave/readme.md) | This example application demonstrates the multi-client feature of the asynchronous mode of the I2C driver by communicating with an external EEPROM and a temperature sensor |
| [I2C Driver Synchronous - I2C EEPROM](apps/driver/i2c/sync/i2c_eeprom/readme.md) | This example application demonstrates how to use the I2C driver in synchronous mode to perform read/write operations on an EEPROM |
| [I2C Driver Synchronous - I2C multi slave](apps/driver/i2c/sync/i2c_multi_slave/readme.md) | This example application demonstrates the multi-client feature of the synchronous mode of the I2C driver by communicating with an external EEPROM and a temperature sensor |
| [I2C EEPROM driver - AT24 EEPROM read write](apps/driver/i2c_eeprom/at24/at24_eeprom_read_write/readme.md) | This example application demonstrates how to use the AT24 driver to perform read and write operations on AT24 series of EEPROM |
| [SPI driver asynchronous - SPI multi slave](apps/driver/spi/async/spi_multi_slave/readme.md) | This example application demonstrates the multi client feature of the asynchronous mode of the SPI driver by reading and writing to two EEPROMs connected to the same SPI bus |
| [SPI Driver Synchronous - Spi multi slave](apps/driver/spi/sync/spi_multi_slave/readme.md) | This example application demonstrates the multi client feature of the synchronous mode of the SPI driver by reading and writing to two EEPROMs connected to the same SPI bus |
| [SPI EEPROM driver - AT25 EEPROM read write](apps/driver/spi_eeprom/at25/at25_eeprom_read_write/readme.md) | This example application demonstrates how to use the AT25 driver to perform read and write operations on AT25 series of EEPROM |
| [USART driver asynchronous - USART Echo](apps/driver/usart/async/usart_echo/readme.md) | This example application demonstrates the asynchronous mode of the USART driver by echoing the received characters |
| [USART Driver Synchronous - Usart echo](apps/driver/usart/sync/usart_echo/readme.md) | This example application demonstrates the synchronous mode of the USART driver by echoing the received characters |
| [FAT filesystem using NVM Media](apps/fs/nvm_fat/readme.md) | This application shows an example of implementing a FAT disk in the device internal Flash memory |
| [FAT filesystem using SDSPI driver and SPI PLIB](apps/fs/sdspi_fat/readme.md) | This application shows an example of using the MPLAB Harmony File System to access and modify the contents of a SD card using the SDSPI driver and the SPI PLIB |
| [EEPROM Emulator library read write](apps/library/eeprom_emulator/eeprom_emulator_read_write/readme.md) | This application example demonstrates how to read and write to the Emulated EEPROM memory space using the EEPROM Emulator library |
| [FreeRTOS basic](apps/rtos/freertos/basic_freertos/readme.md) | This example application demonstrates context switching between four tasks of different priorites. Two tasks run periodically while the other two tasks are event driven |
| [Time System Service multi client](apps/system/time/sys_time_multiclient/readme.md) | This example application demonstrates the multi-client system timer functionality |

____

[![License](https://img.shields.io/badge/license-Harmony%20license-orange.svg)](https://github.com/Microchip-MPLAB-Harmony/core_apps_sam_g55/blob/master/mplab_harmony_license.md)
[![Latest release](https://img.shields.io/github/release/Microchip-MPLAB-Harmony/core_apps_sam_g55.svg)](https://github.com/Microchip-MPLAB-Harmony/core_apps_sam_g55/releases/latest)
[![Latest release date](https://img.shields.io/github/release-date/Microchip-MPLAB-Harmony/core_apps_sam_g55.svg)](https://github.com/Microchip-MPLAB-Harmony/core_apps_sam_g55/releases/latest)
[![Commit activity](https://img.shields.io/github/commit-activity/y/Microchip-MPLAB-Harmony/core_apps_sam_g55.svg)](https://github.com/Microchip-MPLAB-Harmony/core_apps_sam_g55/graphs/commit-activity)
[![Contributors](https://img.shields.io/github/contributors-anon/Microchip-MPLAB-Harmony/core_apps_sam_g55.svg)]()

____

[![Follow us on Youtube](https://img.shields.io/badge/Youtube-Follow%20us%20on%20Youtube-red.svg)](https://www.youtube.com/user/MicrochipTechnology)
[![Follow us on LinkedIn](https://img.shields.io/badge/LinkedIn-Follow%20us%20on%20LinkedIn-blue.svg)](https://www.linkedin.com/company/microchip-technology)
[![Follow us on Facebook](https://img.shields.io/badge/Facebook-Follow%20us%20on%20Facebook-blue.svg)](https://www.facebook.com/microchiptechnology/)
[![Follow us on Twitter](https://img.shields.io/twitter/follow/MicrochipTech.svg?style=social)](https://twitter.com/MicrochipTech)

[![](https://img.shields.io/github/stars/Microchip-MPLAB-Harmony/core_apps_sam_g55.svg?style=social)]()
[![](https://img.shields.io/github/watchers/Microchip-MPLAB-Harmony/core_apps_sam_g55.svg?style=social)]()