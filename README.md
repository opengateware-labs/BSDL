# FPGA BSDL Files Repository

This repository contains Boundary Scan Description Language (BSDL) files for various FPGA manufacturers. These files are essential for boundary scan testing, JTAG programming, and hardware debugging of FPGA devices.

## Contents

Currently, this repository includes BSDL files for the following FPGA manufacturers:

- **Altera (Intel)** - Cyclone, Cyclone II, Cyclone III, Cyclone IV, Cyclone V, Cyclone 10 LP, and MAX10 families
- **Lattice** - ECP5 family
- **Xilinx** - Artix-7, Zynq, Zynq UltraScale+, and Zynq UltraScale+ RFSOC families
- **Gowin** *(files to be added)*
- **Efinix** *(files to be added)*

## Repository Structure

The repository is organized hierarchically by manufacturer and device family:

```
.
├── Altera (Intel)
│   ├── Cyclone
│   ├── Cyclone 10 LP
│   ├── Cyclone II
│   ├── Cyclone III
│   ├── Cyclone IV
│   ├── Cyclone V
│   └── MAX10
│       └── IEEE 1532
├── Lattice
│   └── ECP5
├── Xilinx
│   ├── Artix-7
│   ├── Zynq
│   ├── Zynq UltraScale+
│   └── Zynq UltraScale+ RFSOC
├── Gowin
└── Efinix
```

## What are BSDL Files?

BSDL (Boundary Scan Description Language) files are IEEE 1149.1 compliant descriptions of how JTAG is implemented in a particular device. They contain information about:

- Pin mappings
- Boundary scan register descriptions
- Instructions supported by the device
- ID codes
- Other device-specific information needed for boundary scan operations

These files are typically used with JTAG tools to perform:
- Device programming
- Boundary scan testing
- In-system debugging
- Hardware validation

## Usage

These BSDL files can be imported into various JTAG tools and boundary scan software, including:

- Xilinx Vivado/ISE
- Intel Quartus Prime
- Lattice Diamond/Radiant
- JTAG Technologies software
- Corelis ScanExpress
- XJTAG
- And other boundary scan test equipment

## Contributing

Contributions to expand the collection are welcome! If you'd like to add BSDL files for new devices or manufacturers, please:

1. Maintain the existing directory structure
2. Ensure files are from official sources or verified against official documentation
3. Submit a pull request with a clear description of the added files

## Disclaimer

These BSDL files are collected from various sources and provided as-is. While efforts are made to ensure accuracy, please verify critical files against manufacturer-provided originals before use in production environments.

## License

These files are provided for engineering reference and debugging purposes. All files remain the intellectual property of their respective manufacturers. Please consult the specific manufacturer's licensing terms for usage restrictions.

## Contact

For questions, suggestions, or issues with the repository, please open an issue in the repository's issue tracker.