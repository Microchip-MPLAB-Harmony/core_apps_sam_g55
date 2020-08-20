[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# SPI Driver Synchronous - Spi multi slave

This example application demonstrates the multi client feature of the synchronous mode of the SPI driver by reading and writing to two EEPROMs connected to the same SPI bus.

## Description

The application uses the synchronous mode of the SPI driver and demonstrates the multi client feature by reading and writing to two EEPROMs connected to the same SPI bus. The example also demonstrates how to setup two different client transfers at two different baud rates.

The example has three RTOS threads for the purpose:

APP_EEPROM1_Tasks: This thread performs write-read operation on the first EEPROM
APP_EEPROM2_Tasks: This thread performs write-read operation on the second EEPROM
APP_MONITOR_Tasks: This thread checks the status of the EEPROM transfers and turns on the LED if the transfers are successful

The application communicates with two [EEPROM 3 click boards](https://www.mikroe.com/eeprom-3-click) that has AT24CM02 EEPROM on it.

## Downloading and building the application

To clone or download this application from Github, go to the [main page of this repository](https://github.com/Microchip-MPLAB-Harmony/core_apps_sam_g55) and then click Clone button to clone this repository or download as zip file.
This content can also be downloaded using content manager by following these [instructions](https://github.com/Microchip-MPLAB-Harmony/contentmanager/wiki).

Path of the application within the repository is **apps/driver/spi/sync/spi_multi_slave/firmware** .

To build the application, refer to the following table and open the project using its IDE.

| Project Name      | Description                                    |
| ----------------- | ---------------------------------------------- |
| sam_g55_xpro_freertos.X | MPLABX project for [SAM G55 Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamg55-xpro) |
|||

## Setting up the hardware

The following table shows the target hardware for the application projects.

| Project Name| Board|
|:---------|:---------:|
| sam_g55_xpro_freertos.X | [SAM G55 Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamg55-xpro) |
|||

- To run the demo, the following additional hardware are required:
    - Two [EEPROM 4 click boards](https://www.mikroe.com/eeprom-4-click)
	- Two [mikroBUS Xplained Pro boards](https://www.microchip.com/developmenttools/ProductDetails/ATMBUSADAPTER-XPRO)

### Setting up [SAM G55 Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamg55-xpro)

- Install [EEPROM 4 click boards](https://www.mikroe.com/eeprom-4-click) on the [mikroBUS Xplained Pro boards](https://www.microchip.com/developmenttools/ProductDetails/ATMBUSADAPTER-XPRO

- Connect the [mikroBUS Xplained Pro boards](https://www.microchip.com/developmenttools/ProductDetails/ATMBUSADAPTER-XPRO) on EXT1 and EXT3 headers of the [SAM G55 Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamg55-xpro)

- Connect the Debug USB port on the board to the computer using a micro USB cable

## Running the Application

1. Build and Program the application using its IDE.
2. The LED indicates success or failure.
    - The LED turns ON when the data read from the EEPROMs matches with the data written to the EEPROMs.

Refer to the following table for LED name:

| Board | LED Name |
| ----- | -------- |
|  [SAM G55 Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamg55-xpro) | LED0 |
|||