# Original OWF by Kwiatens™ - (Offgrid Weather Forecaster)
<p align="center">
  <img src="https://github.com/Kwiatens/OWF-Offgrid-Weather-Forecaster/blob/main/images/Original_OWFR1_logo_white.png?raw=true" alt="OWF" />
</p>

OWF™ is an affordable, offgrid, [Meshtastic](https://meshtastic.org/)® powered weather forecaster that does **NOT** use the internet. **Instead it uses its own sensors to calculate weather predictions using an Zambretti algorithm with a couple of custom algorithms**.
When calibrated, it can be over 90% accurate for 12 hour predictions!
More information about the project on [our Discord Server](https://discord.gg/Jbdw9DENTZ)

## Features

- Offgrid weather forecasting based on integrated sensor data only - computed by the board itself.
- The forecaster can send morning and/or on demand weather raports.
- Many OWF units can be linked together to form a more detailed and rich forecast.
- More stuff :)

## Getting Started
Great! So you want to build your own OWF board - that's cool!
You can click [here](https://github.com/Kwiatens/OWF-Offgrid-Weather-Forecaster/blob/main/docs/01_Getting_Started.md) to begin your build.

## Quick OWF R1 Board Hardware Overview

- MCU: Arduino Pro Mini 3.3V @8 MHz + NRF52840 ProMicro
- Transciever: LoRa HT-RA62 ([Meshtastic](https://meshtastic.org/)®)
- Power: Solar + dual or single 18650 Li-Ion socket with charging modules
- Sensor: BME280/BMP280 + optional anemometer
- RTC: DS1302 with backup battery
  
## Repository Structure

| Folder       | Contents                              |
|--------------|----------------------------------------|
| `OWF_Firmware/`  | OWF Firmware                       |
| `OWF_PCB_Files/` | Gerber PCB manufacturing files     |
| `docs/`      | Design notes and protocol description  |
| `images/`    | Photos, diagrams, and renders          |


## Legal
[Meshtastic](https://meshtastic.org/)® is a registered trademark of Meshtastic LLC. Meshtastic software components are released under various licenses. No warranty is provided – use at your own risk.

## Author
Developed by Kwiatens - 2025.
