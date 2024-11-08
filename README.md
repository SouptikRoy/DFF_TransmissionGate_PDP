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

![Block Diagram](C:\Users\Souptik Roy\Pictures\D Flip Flop Transmission Gate.jpg)






