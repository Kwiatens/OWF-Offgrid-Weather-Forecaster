# Building OWF R1 – 01 | Overview and Bill of Materials (BOM)

This section provides an overview of the OWF hardware and a complete Bill of Materials (BOM) needed to build the **OWF R1** board.

The OWF R1 is the baseline version of the Offgrid Weather Forecaster. It features solar-powered operation, an onboard atmospheric sensor, and Meshtastic® LoRa communication.

## Bill of Materials (BOM)

| Item                     | Quantity | Notes                                                                 | Purchase link |
|--------------------------|----------|------------------------------------------------------------------------|----------------|
| Arduino Pro Mini 3.3V    | 1        | **Get the 8 MHz 3.3V Version!** (low power)                                              | [AliExpress](https://pl.aliexpress.com/item/1005006843855788.html?spm=a2g0o.order_list.order_list_main.11.7cac1c24H9nd8a&gatewayAdapt=glo2pol) |
| NRF52840 Pro Micro       | 1        | This board runs Meshtastic® firmware                                   | [AliExpress](https://pl.aliexpress.com/item/1005007738886550.html?spm=a2g0o.order_list.order_list_main.71.7cac1c24H9nd8a&gatewayAdapt=glo2pol) |
| HT-RA62 868MHz LoRa module      | 1        | **Get the 868MHz Version!**                                             | [AliExpress](https://pl.aliexpress.com/item/1005005543917617.html?spm=a2g0o.order_list.order_list_main.112.7cac1c24H9nd8a&gatewayAdapt=glo2pol)               |
| BME280 or BMP280*        | 1        | **Get the 3.3V Version!** I²C air pressure, temperature and humidity sensor*                     | [AliExpress](https://pl.aliexpress.com/item/1005008059227856.html?spm=a2g0o.order_list.order_list_main.5.7cac1c24H9nd8a&gatewayAdapt=glo2pol)               |
| DS1302 RTC Module        | 1        | DS1302 RTC Module (Desolder the oscillator and battery holder, take out the IC from the socket – everything is cheaper that way) |                |
| TP4056 charging module   | 2        | One per 18650 cell                                                     |                |
| 18650 battery holder     | 2        | 2 cell or 1 cell holder                                                |                |
| 1W+ solar panel          | 1        | Must supply at least 5V                                                |                |
| Various resistors/caps   | —        |                                                                        |                |
| Custom PCB (OWF R1)      | 1        | See `/hardware/` folder for Gerber files                               |                |
| Misc. headers and wiring | —        | For connecting modules and debugging                                   |                |


> *BME280 is highly recommended as BMP280 does not measure air humidity - meaning you won't have access to some important features.

