# Original OWF (Offgrid Weather Forecaster)
![OWF](https://github.com/Kwiatens/OWF-Offgrid-Weather-Forecaster/blob/main/images/Original_OWFR1_logo.png?raw=true)
OWF is an affordable, offgrid, [Meshtastic](https://meshtastic.org/)® powered weather forecaster that does **NOT** use the internet. **Instead it uses its own sensors to calculate weather predictions using an Zambretti algorithm with a couple of custom algorithms**.
When calibrated, it can be over 90% accurate for 12 hour predictions!
More information about the project on [our Discord Server](https://discord.gg/Jbdw9DENTZ)

## Features

- Send morning weather raports every day.
- Send a weather raport on demand.
- Send an alert when weather suddenly changed.
- Fully offgrid operation - It does **not** use the internet, WiFi etc.
- Powered by a small 1W solar panel.

## Getting Started

TODO

## OWF R1 Board Hardware Overview

- MCU: Arduino Pro Mini 3.3V @8 MHz + NRF52840 ProMicro
- Transciever: LoRa HT-RA62 ([Meshtastic](https://meshtastic.org/)®)
- Power: Solar + 2 18650 LiIon sockets with charging modules
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
