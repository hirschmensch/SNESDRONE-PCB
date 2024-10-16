# SNESDRONE-PCB

The SNESDRONE-PCB is a custom cartridge designed for the Super Nintendo Entertainment System (SNES). This project allows users to control the internal SPC700 sound chip of the SNES as a synthesizer by using several potentiometers placed on the cartridge. The board can be inserted directly into the SNES, giving real-time control over various sound parameters.

## Features
- **Analog Controls**: Multiple potentiometers to control different aspects of the SPC700 sound chip.
- **Simple Integration**: Fits directly into the SNES cartridge slot.
- **Open-source Firmware**: Firmware available for customizing the interaction with the SPC700 sound chip (see [SNESDRONE-Firmware](https://github.com/michael-hirschmugl/SNESDRONE-Firmware)).

## Branches
- **Master Branch**: Contains the first release version of the PCB, which is fully functional and ready for use.
- **Direct_IO Branch**: In development. This branch focuses on creating a cartridge with an FPGA interface, allowing direct control over the data and address buses of the SNES. The design uses a Digilent Arty Z7 board. See the `direct_io` branch for the latest updates.

## Documentation and More Information
For more detailed information about the project, visit the [Hackaday page](https://hackaday.io/project/162633-snes-drone).

## Installation
To use the SNESDRONE cartridge, simply insert it into the SNES, and the potentiometers will allow you to manipulate sound parameters of the SPC700 in real-time. Further instructions on assembly and usage can be found in the documentation.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
