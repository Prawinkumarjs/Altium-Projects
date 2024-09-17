# Battery Level Indicator PCB Design

This project involves designing a **Battery Level Indicator** using **Altium Designer**, an industry-standard ECAD tool. The project demonstrates the creation of a PCB for monitoring the battery voltage levels and visually indicating them using LEDs.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Design Overview](#design-overview)
- [Bill of Materials (BOM)](#bill-of-materials-bom)
- [PCB Design](#pcb-design)
- [Schematic Design](#schematic-design)
- [Simulation and Testing](#simulation-and-testing)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

A battery level indicator is a simple yet essential circuit that monitors the charge in a battery and provides a visual indication through LEDs. This project utilizes **Altium Designer** for creating a professional-grade PCB, allowing for compact and efficient implementation of the indicator circuit.

## Features

- **Voltage Range**: Works with a wide range of battery voltages.
- **LED Indicators**: Shows different levels of battery charge.
- **Compact PCB Design**: Designed using Altium's advanced features for a small footprint.
- **Power Efficiency**: Low power consumption components.

## Design Overview

This PCB design includes:

- Voltage divider network to sense battery voltage.
- Comparators to compare the battery voltage against reference levels.
- LEDs to indicate different battery charge levels.
- Power supply circuits to ensure stable operation.

## Bill of Materials (BOM)

| Component         | Description                        | Quantity |
|-------------------|------------------------------------|----------|
| Resistors          | 1kΩ, 10kΩ, 100kΩ (Various values)  | X        |
| LEDs               | Red, Green, Yellow (Battery Level) | 3        |
| LM3914/Comparator IC| For voltage comparison            | 1        |
| Battery Connector  | JST or Pin Header                  | 1        |
| Capacitors         | 10uF, 100nF                       | X        |

## PCB Design

The PCB was designed using **Altium Designer** with the following specifications:

- **Layers**: 2-layer board
- **Size**: Compact form factor
- **Connectors**: Standard battery connectors and programming headers
- **Mounting**: Through-hole or SMD components based on availability

### PCB Layouts:

- **[PCB Layout - Top](https://github.com/Prawinkumarjs/Altium-Projects/blob/main/Battery%20Level%20Indicator/PCB%20Prints-1.png)**
  ![PCB Layout - Top](https://github.com/Prawinkumarjs/Altium-Projects/blob/main/Battery%20Level%20Indicator/PCB%20Prints-1.png)
- **[PCB Layout - Bottom](https://github.com/Prawinkumarjs/Altium-Projects/blob/main/Battery%20Level%20Indicator/PCB%20Prints-2.png)**

  ![PCB Layout - Bottom](https://github.com/Prawinkumarjs/Altium-Projects/blob/main/Battery%20Level%20Indicator/PCB%20Prints-2.png)



### 3D Model:

- **[3D View of PCB](https://github.com/Prawinkumarjs/Altium-Projects/blob/main/Battery%20Level%20Indicator/PCB%203D%20Print.png)**

  ![3D View of PCB](https://github.com/Prawinkumarjs/Altium-Projects/blob/main/Battery%20Level%20Indicator/PCB%203D%20Print.png)

## Schematic Design

The schematic includes:

1. A voltage divider to measure the battery voltage.
2. A comparator circuit to compare different voltage thresholds.
3. LED drivers to visually display the battery level.
4. Power regulation to ensure consistent performance.

### Schematic:

- **[View the Schematic](https://github.com/Prawinkumarjs/Altium-Projects/blob/main/Battery%20Level%20Indicator/Schematic%20Prints.png)**
 
 ![View the Schematic](https://github.com/Prawinkumarjs/Altium-Projects/blob/main/Battery%20Level%20Indicator/Schematic%20Prints.png)


## Simulation and Testing

- The design was simulated to ensure proper voltage levels at different stages of the circuit.
- Test points were added to the PCB layout for easy troubleshooting and verification during testing.

## Installation

1. Download the project files from the repository.
2. Open the project using **Altium Designer**.
3. Perform DRC (Design Rule Check) and ERC (Electrical Rule Check).
4. Export Gerber files for PCB manufacturing.
5. Assemble the PCB and test using a real battery.

## Contributing

Contributions are welcome! If you have any ideas or improvements, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
