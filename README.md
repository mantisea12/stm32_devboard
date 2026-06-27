# STM32H7 HDI Development Board

An 8-layer HDI development board based on the STM32H7A3AG (UFBGA169, 0.5 mm pitch package).

## Features

- STM32H7A3AG microcontroller
- ESP32 wireless coprocessor
- External flash memory
- microSD card interface
- One UART interface for the STM32H7, and another for the ESP32.
- USB connectivity
- High-density routing

## Design Information

- PCB Layers: 8
- HDI construction with microvias
- Package: UFBGA169 (0.5 mm pitch)
- Software: KiCad

## Repository Contents

- KiCad project files
- Manufacturing Gerbers
- BOM
- Board renders
- PCB screenshots

## Notes

An external SDRAM interface was originally planned for this design but was removed during layout due to routing density and project scope considerations. Some disconnected schematic artifacts related to the removed SDRAM interface remain and have no effect on the final design.

This project was created to explore high-density multilayer PCB design, BGA fanout techniques, and advanced embedded hardware layout.
