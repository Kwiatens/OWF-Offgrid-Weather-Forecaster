# Original OWF by Kwiatens™ - (Offgrid Weather Forecaster)
<p align="center">
  <img src="https://github.com/Kwiatens/OWF-Offgrid-Weather-Forecaster/blob/main/images/Original_OWFR1_logo_white.png?raw=true" alt="OWF" />
</p>

OWF™ is an affordable, DiY, fully offgrid, [Meshtastic](https://meshtastic.org/)® powered weather forecaster that does **NOT** use the internet for its forecasts. **Instead it uses its own sensors to calculate weather predictions using a couple of custom algorithms that are based on Zambretti method.**
When calibrated, it can be over 90% accurate for 12 hour predictions!

The board can be build with moderate knowledge of electronics, soldering etc (SMD Components are present) 
The project has a step by step guide that will go through everything (including common issues).

Don’t worry if you don’t want to build one yourself - **we’ll be offering them for sale once everything is ready!**

More information about the project on [our Discord Server](https://discord.gg/Jbdw9DENTZ).

### **Project is WIP**

## Getting Started

To get started, head over to the [**Building OWF**](https://github.com/Kwiatens/OWF-Offgrid-Weather-Forecaster/blob/main/docs/00_Getting_Started.md) section, where you'll find everything you need to assemble your own device - including hardware options, component lists, and step-by-step instructions.

## Features
- 100% off-grid operation, no MQTT, no internet connection needed. Everything is computed and ran directly on the OWF board itself.
- Weather forecasting based on integrated sensor data only.
- The forecaster can send morning and on demand weather raports, featuring both current weather data and the prediction itself.
- Emergency weather alerts such as a high wind or storm warning.
- 3D Printable enclosure and mounting system.

## Currenly working on (OWF R1)
- Feedback based calibration algorithm
- Hourly weather forecast
  
## Future plans (OWF R2)

- OWF App for PC and Mobile for convinient OTA updating, viewing data and configuraing the device.
- More addons like: anemometer, lightning detection unit, rain guage etc.
- Making many OWF units to link together to form a mesh of forecasters - more detailed and rich forecast.
- Better hardware (RTC, Sensors, MCU etc.)

## Quick OWF R1 Board Hardware Overview

- MCU: Arduino Pro Mini 3.3V @8 MHz + NRF52840 ProMicro
- Transciever: LoRa HT-RA62 ([Meshtastic](https://meshtastic.org/)®)
- Power: Solar + dual or single 18650 Li-Ion socket with charging modules
- Sensor: BME280/BMP280 + optional anemometer
- RTC: DS1302 with backup battery

## Legal
Original OWF by Kwiatens™
No warranty is provided – use at your own risk. This device is intended for personal and educational purposes only and is not certified for professional, commercial, or safety-critical applications, including but not limited to aviation, maritime, or meteorological services. Do not use near airports or in any environment where interference with communications, navigation, or safety systems could occur.
The OWF may produce inaccurate or incomplete data. Do not rely on this device for decisions involving personal safety, life-or-death situations, or the protection of property. The creator assumes no responsibility for any damage, injury, loss, or legal consequences arising from the use or misuse of this product.

“OWF” and “Original OWF by Kwiatens” are unregistered trademarks of Kwiatens.  
Used to indicate the original maker and identity of the Offgrid Weather Forecaster project.

[Meshtastic](https://meshtastic.org/)® is a registered trademark of Meshtastic LLC. Meshtastic software components are released under various licenses. No warranty is provided – use at your own risk.

## Author
Developed by Kwiatens - 2025.

© 2025 Kwiatens. All rights reserved.  
