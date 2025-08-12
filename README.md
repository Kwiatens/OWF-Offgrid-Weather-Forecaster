# Original OWF by Kwiatens™ - (Offgrid Weather Forecaster)
<p align="center">
  <img src="https://github.com/Kwiatens/OWF-Offgrid-Weather-Forecaster/blob/main/images/Original_OWFR1_logo_white.png?raw=true" alt="OWF" />
</p>

OWF™ is an affordable, DiY, offgrid, [Meshtastic](https://meshtastic.org/)® powered weather forecaster that does **NOT** use the internet. **Instead it uses its own sensors to calculate weather predictions using a couple of custom algorithms that are based on Zambretti method.**
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

## Future plans

- OWF Flasher website for convinient device flashing and configuring.
- More addons like: anemometer, lightning detection unit, rain guage etc.
- Making many OWF units to link together to form a more detailed and rich forecast.

## Quick OWF R1 Board Hardware Overview

- MCU: Arduino Pro Mini 3.3V @8 MHz + NRF52840 ProMicro
- Transciever: LoRa HT-RA62 ([Meshtastic](https://meshtastic.org/)®)
- Power: Solar + dual or single 18650 Li-Ion socket with charging modules
- Sensor: BME280/BMP280 + optional anemometer
- RTC: DS1302 with backup battery

  
## Legal
Original OWF by Kwiatens™  
No warranty is provided – use at your own risk.

“OWF” and “Original OWF by Kwiatens” are unregistered trademarks of Kwiatens.  
Used to indicate the original maker and identity of the Offgrid Weather Forecaster project.

[Meshtastic](https://meshtastic.org/)® is a registered trademark of Meshtastic LLC. Meshtastic software components are released under various licenses. No warranty is provided – use at your own risk.

## Author
Developed by Kwiatens - 2025.

© 2025 Kwiatens. All rights reserved.  
