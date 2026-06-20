# kirawnik

> From Belarusian: head, manager

Compact ESP32-C6 board for powering on or rebooting a Framework Desktop over Zigbee or Wi-Fi.

![kirawnik 3d view](https://kekcheburec.github.io/kirawnik/rotating.gif)

## Overview

kirawnik sits between the motherboard and the case power button cable. It uses the 5V SB pin exposed on the Framework Desktop front panel connector, keeping the ESP32-C6 powered even while the system is shut down or asleep.

For easier installation, the board has silkscreen markings for the cable connections. The external antenna should be connected to the uFL (a.k.a u.FL / IPX / IPEX) connector and mounted on non-metal parts.

Firmware can be built manually or with ESPHome. With ESP32-C6 Zigbee support, the board can connect to many smart home systems and work offline.

## References

- [Front panel connector location and pinout](https://knowledgebase.frame.work/front-panel-io-connectors-amd-ryzen-ai-max-300-series-Hk3SXolHxg)
- [Framework Desktop motherboard connector schematic](https://github.com/FrameworkComputer/Framework-Desktop/blob/main/Mainboard/Mainboard_Interfaces_Schematic_Framework_Desktop_Ryzen_AI_Max.pdf)

## Disclaimer

No warranties of any kind
