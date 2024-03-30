# STM32G041F8P6 Development Board

## Overview
This repository hosts the design files for a custom development board centered around the STM32G041F8P6 microcontroller. Born out of the necessity for a simple, accessible development platform for this specific STM32 variant, this project is tailored for both development and educational purposes. Designed with Altium Designer, the project encompasses the schematic, PCB source files, Bill of Materials (BOM), and Gerber files necessary for manufacturing.

## Project Background
The motivation behind this project was the lack of readily available development boards for the STM32G041F8P8 microcontroller. Aiming to fill this gap, this board has been developed to offer a straightforward, effective tool for both learners and developers alike, particularly useful in space-sensitive projects due to the microcontroller's small 20TSSOP footprint.

## Features
- **Microcontroller**: STM32G041F8P6, ideal for space-sensitive projects.
- **Power Supply**: Wide input voltage range from 4.5V to 30V.
- **Programming**: Supports programming via SWD, compatible with STLink and other third-party SWD programmers.
- **Output**: Includes an LED to indicate output.
- **Prototyping Friendly**: Features headers for all outputs, making it ideal for prototype development.

## File Structure
- `Schematic/`: Schematic files for the development board.
- `PCB/`: PCB design files created with Altium Designer.
- `BOM/`: Bill of Materials, listing all components required for the board.
- `Gerber/`: Gerber files for PCB manufacturing.

## 3D Design and Final Assembly
### 3D Design
![3D Design of the PCB](/images/Top.png)

### Final Assembly
![Final Assembly of the PCB](/images/Top_assembled.png)

## Getting Started
To use these design files:
1. Ensure you have Altium Designer installed to open and edit the PCB and schematic files.
2. Download the Gerber files and submit them to a PCB manufacturer of your choice, such as JLCPCB, PCBway, or others.
3. You can opt for the manufacturer to assemble the components or do it yourself.
4. Program the board using an STLink or any compatible third-party SWD programmer.

## Manufacturing
The Gerber files provided are ready for manufacturing. You are free to choose any PCB manufacturer for fabrication and assembly. We recommend double-checking the BOM and Gerber files before submission to ensure compatibility with your chosen manufacturer's requirements.

## Contributing
We welcome contributions to this project! Whether you have suggestions for improvement, new features, or have encountered an issue with the PCB design, your input is highly valued. Feel free to submit pull requests or open issues for discussion.

## License
This project is licensed under the MIT License, which allows for both personal and commercial use, modification, distribution, and private use as long as the original copyright and license notice are included with any substantial portion of the work. For full license text, see the LICENSE file in this repository.

## Contact
Should you have any questions, suggestions, or issues, please feel free to reach out via GitHub issues. We are open to collaborations and keen to hear from anyone interested in improving or utilizing this development board.

