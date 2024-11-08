# Optimized D Flip-Flop Design Using Transmission Gate Technology

This project presents an optimized D Flip-Flop circuit design using transmission gates, specifically targeting reduced Power-Delay Product (PDP) for low-power, high-speed VLSI applications. The design leverages the SkyWater 130nm Process Design Kit (PDK) and is implemented and simulated using the eSim and SPICE tools.

## Project Overview

Flip-flops are fundamental elements in sequential digital circuits, and optimizing their performance is crucial in VLSI design. This project uses transmission gate technology to minimize the transistor count, reduce power consumption, and achieve efficient data flow. By carefully controlling data paths and reducing switching delays, this design achieves an improved PDP, making it suitable for modern power-sensitive applications.

### Features
- **Optimized for Power-Delay Product (PDP)**: The design minimizes PDP through the use of transmission gates and efficient data buffering.
- **Implemented in eSim**: Schematic design and simulations are done using eSim for accurate results.
- **SkyWater 130nm PDK Compatibility**: Utilizes the SkyWater 130nm technology node, widely used in low-power applications.

## Circuit Components and Configuration

1. **Transmission Gates (TG1 and TG2)**:
   - Master-Slave configuration using NMOS and PMOS transistors to control data flow.
2. **Inverters**:
   - **Clock Inverter**: Generates the inverted clock (CLK’) from the main clock (CLK).
   - **Data Buffer Inverter**: Buffers the signal between master (TG1) and slave (TG2) stages.
3. **Clock Signals (CLK and CLK’)**:
   - **CLK**: The main clock signal for data input.
   - **CLK’**: Inverted clock signal generated by the clock inverter.

## Block Diagram

The block diagram below shows the basic structure of the D Flip-Flop design.
![Block Diagram]
## Performance Parameters
The key performance parameters measured in this design include:
- **Power Consumption**: Measured in microwatts (µW), focusing on low-power design.
- **Delay**: The propagation delay of the circuit, aiming for minimal delay.
- **Power-Delay Product (PDP)**: Calculated to evaluate the energy efficiency of the flip-flop.

## Specifications
Detailed specifications of the D flip-flop design:
- **Technology Node**: 130nm SkyWater PDK
- **Input Voltage**: Standard operating voltage for the transmission gates and inverters.
- **Control Signals**: Clock and inverted clock signals control the transmission gates.
- **Output**: Q output with precise timing characteristics.

## Open Source Tools Used
This project was developed using the following open-source tools:
- **eSim** - for circuit design and simulation
- **KiCad** - for creating and managing circuit schematics
- **NGSpice** - for SPICE simulations of the D flip-flop
- **SkyWater PDK** - open-source process design kit for 130nm technology node

## Installation in Windows
Follow these steps to set up the project in a Windows environment:

1. **Download and Install Required Tools**:
   - [eSim](https://esim.fossee.in/) for circuit simulation.
   - [KiCad](https://kicad.org/) for schematic creation.
   - [NGSpice](http://ngspice.sourceforge.net/) for SPICE simulation.
   - [SkyWater PDK](https://github.com/google/skywater-pdk) for technology-specific parameters.

2. **Clone the Project Repository**:
   ```bash
   git clone https://github.com/SouptikRoy/https://github.com/SouptikRoy/DFF_TransmissionGate_PDP







