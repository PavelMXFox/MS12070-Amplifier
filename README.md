# Audio Amplifier System Design
##  Overview
This project is a professional-grade audio amplifier system featuring dual MA12070P Class-D amplifier chips in a 2×BTL configuration. The design includes a complete power supply section, digital signal processing (DSP) core, and control interfaces.

## Key Features
* Dual Channel Bi-Amplifier: 2×BTL configuration with MA12070P chips
* Digital Control: Integrated DSP for advanced audio processing
* Power Supply: 24V input with comprehensive protection circuitry
* Interfaces: I2C control, ADC inputs, and digital audio inputs
* Protection: Overvoltage, reverse polarity, and thermal monitoring

## Hardware Components
* Main Amplifiers: MA12070P Class-D amplifiers
* DSP Core: ADAU1452 audio processor
* Power Management: ADM1032 for rail monitoring
* Control MCU: STM32 microcontroller
* Audio Interfaces: PCM1808 for digital audio input

## Block Diagram Overview
The system consists of the following main sections:
* Power Section: 24V input with protection and distribution
* Amplifier Section: Dual MA12070P channels with complete driver circuitry
* DSP Section: Audio processing core with memory
* Control Section: MCU and interface circuits
* Audio Section: Input conditioning and output drivers

## Documentation
* Schematics: Detailed schematics for all sections
* PCB Layout: Professional-grade layout with proper grounding and power distribution
* Bill of Materials: Complete list of components
* Assembly Guide: Step-by-step assembly instructions
## License
This project is released under the TAPR Open Hardware License. All files are provided "as is" without warranty. For more details, see the LICENSE.TXT file.

## Contributions
* Original Power Supply Section: Based on Open Hardware DSP Platform (github.com:ohdsp/DSP-ADAU1452.git) under TAPR OHL
* Main Design: Developed by Pavel Dmitriev
* Modifications: See CHANGES.TXT for detailed list of changes

## How to Use
* Review the schematics and documentation
* Verify component compatibility
* Follow assembly guidelines
* Program the DSP and MCU
* Perform system calibration

## Known Issues
None reported at this time

## Contact
For questions or contributions, please contact:
GitHub: https://github.com/PavelMXFox

## Version History
* Initial release: November 2026
* Based on design principles from Open Hardware DSP Platform (github.com:ohdsp/DSP-ADAU1452.git)