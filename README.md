# USB Expansion Dock PCB Design (SL2.1A)

A compact and efficient 4-port USB 2.0 hub design based on the Corechip SL2.1A controller. This project includes the schematic and PCB layout designed using [JLCEDA (EasyEDA)](https://lceda.cn/).

![3D Preview](pic/3D_USB%20Expansion%20Dock%20PC.png)

## Overview

This USB dock expands a single USB connection into four downstream USB 2.0 ports. It features a modern USB Type-C input interface and four standard USB Type-A output interfaces, making it suitable for expanding connectivity on laptops, desktops, and embedded systems.

The design prioritizes simplicity and cost-effectiveness using the widely available SL2.1A hub controller.

## Features

- **Controller**: Corechip SL2.1A (USB 2.0 Hub Controller).
- **Speed**: Supports USB 2.0 High-Speed (480 Mbps) and Full-Speed (12 Mbps).
- **Input Interface**: 1x USB Type-C (UFP - Upstream Facing Port).
- **Output Interface**: 4x USB Type-A (DFP - Downstream Facing Ports).
- **Power**: 
  - Bus-powered design (draws power from the host).
  - Power LED indicator for status.
  - Over-current protection using fuses.
- **PCB**: Compact layout designed for ease of manufacturing.

## Hardware Preview

### Schematic
The design utilizes the SL2.1A for signal distribution.
![Schematic](pic/SCH_USB%20Docking%20Station%20Schematic.png)

### PCB Layout
Optimized for signal integrity and compact form factor.
![PCB Layout](pic/PCB_USB%20Expansion%20Dock.png)

## Getting Started

1. **JLCEDA Project**: You can open the `.eprj` or `.json` file (if available) or the project folder in JLCEDA Standard/Pro edition.
2. **Fabrication**: Export the Gerber files from the PCB editor to manufacture the board.
3. **Assembly**: Solder the components according to the BOM (Bill of Materials). 
   - Ensure the SL2.1A is oriented correctly.
   - Pay attention to the USB Type-C connector soldering as the pins are fine-pitched.

## License

This project is open-source. Please check the license file for details (if applicable).
