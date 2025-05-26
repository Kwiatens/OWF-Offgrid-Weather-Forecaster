# Original OWF (Offgrid Weather Forecaster)

OWF is an affordable, offgrid, [Meshtastic](https://meshtastic.org/)® powered weather forecaster that does **NOT** use the internet. **Instead it uses its own sensors to calculate weather predictions using an Zambretti algorithm with a couple of custom algorithms**.
When calibrated, it can be over 90% accurate for 12 hour predictions!
More information about the project on [our Discord Server](https://discord.gg/Jbdw9DENTZ)

## Features

- Fully offgrid operation (No internet etc. - everything is running on the board itself)

## OWF R1 Hardware Overview

- MCU: Arduino Pro Mini 3.3V @8 MHz + NRF52840 ProMicro
- Power: Solar + 2 18650 LiIon sockets with charging modules
- Sensor: BME280/BMP280 + optional anemometer
- RTC
  
## Repository Structure

| Folder       | Contents                              |
|--------------|----------------------------------------|
| `firmware/`  | Arduino source code and libraries      |
| `hardware/`  | Schematic, PCB layout, BOM             |
| `docs/`      | Design notes and protocol description  |
| `images/`    | Photos, diagrams, and renders          |

## Getting Started

TODO

## Legal

NRF52 + HT-RA62 circuitry based on [fakeTec PCB](https://github.com/gargomoma/fakeTec_pcb).
[Meshtastic](https://meshtastic.org/)® is a registered trademark of Meshtastic LLC. Meshtastic software components are released under various licenses. No warranty is provided – use at your own risk.

## Author
Developed by Kwiatens - 2025.
