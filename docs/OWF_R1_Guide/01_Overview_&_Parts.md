# Building OWF – 01 | Overview and Bill of Materials (BOM)

This section provides an overview of the OWF hardware and a complete Bill of Materials (BOM) needed to build the **OWF R1** board.

The OWF R1 is the baseline version of the Offgrid Weather Forecaster. It features solar-powered operation, an onboard atmospheric sensor, and Meshtastic® LoRa communication.

## Bill of Materials (BOM)

| Item                     | Quantity | Notes                                                                 | Example Link |
|--------------------------|----------|------------------------------------------------------------------------|--------------|
| Arduino Pro Mini 3.3V    | 1        | 8 MHz version (low power)                                              | [AliExpress](https://www.aliexpress.com/wholesale?SearchText=arduino+pro+mini+3.3v) |
| NRF52840 Pro Micro       | 1        | This board runs Meshtastic® firmware                                   | |
| HT-RA62 LoRa module      | 1        | Or similar SX1262-based module                                         | |
| BME280 or BMP280         | 1        | I²C air pressure, temperature and humidity sensor*                     | |
| DS1302 RTC + socket      | 1        | With CR2032 battery                                                    | |
| TP4056 charging module   | 2        | One per 18650 cell                                                     | |
| 18650 battery holder     | 2        | Flat or staggered layout                                               | |
| 1W+ solar panel          | 1        | Must supply at least 5V in sunlight                                    | |
| Various resistors/caps   | —        | See schematic                                                          | |
| Custom PCB (OWF R1)      | 1        | See `/hardware/` folder for Gerber files                               | |
| Misc. headers and wiring | —        | For connecting modules and debugging                                   | |

*BME280 Highly recommended as BMP280 does not measure air humidity - meaning you won't have access to some important features.
> You can order most of these components from the links attached in the table.
