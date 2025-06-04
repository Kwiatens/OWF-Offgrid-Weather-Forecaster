# Original OWF by Kwiatens™ - (Offgrid Weather Forecaster)
<p align="center">
  <img src="https://github.com/Kwiatens/OWF-Offgrid-Weather-Forecaster/blob/main/images/Original_OWFR1_logo_white.png?raw=true" alt="OWF" />
</p>

OWF™ is an affordable, offgrid, [Meshtastic](https://meshtastic.org/)® powered weather forecaster that does **NOT** use the internet. **Instead it uses its own sensors to calculate weather predictions using an Zambretti algorithm with a couple of custom algorithms**.
When calibrated, it can be over 90% accurate for 12 hour predictions!

More information about the project on [our Discord Server](https://discord.gg/Jbdw9DENTZ).

## Getting Started

Great! So you want to build your own OWF board, huh :p

To get started, head over to the [**Building OWF**](https://github.com/Kwiatens/OWF-Offgrid-Weather-Forecaster/blob/main/docs/00_Getting_Started.md) section, where you'll find everything you need to assemble your own device - including hardware options, component lists, and step-by-step instructions.
## Features

- Offgrid weather forecasting based on integrated sensor data only - computed by the board itself.
- The forecaster can send morning and on demand weather raports, featuring both current weather data and the prediction itself.
- Emergency weather alerts such as a high wind or storm warning.
- Many OWF units can be linked together to form a more detailed and rich forecast.
- More stuff :)

## Future plans

- Anemometer addon
- Lightning detector addon

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
