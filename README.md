<div align="center">

# UART Communication Protocol using VHDL

### FPGA-Based UART Design & Functional Verification using AMD Vivado 2023.2

A complete implementation of the UART (Universal Asynchronous Receiver Transmitter) communication protocol in VHDL featuring a Baud Rate Generator, UART Transmitter, UART Receiver, RTL Design, Functional Simulation and FPGA-oriented architecture.

---

![Language](https://img.shields.io/badge/Language-VHDL-blue?style=for-the-badge)

![Tool](https://img.shields.io/badge/Tool-AMD%20Vivado%202023.2-orange?style=for-the-badge)

![FPGA](https://img.shields.io/badge/FPGA-Artix--7-success?style=for-the-badge)

![Simulation](https://img.shields.io/badge/Simulation-Passed-brightgreen?style=for-the-badge)

![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)

</div>

---

# Project Overview

UART (Universal Asynchronous Receiver Transmitter) is one of the most widely used asynchronous serial communication protocols in embedded systems.

This project implements a complete UART communication system in **VHDL**, including:

- Baud Rate Generator
- UART Transmitter
- UART Receiver
- Top-Level Integration
- Behavioral Testbench

The complete design has been developed and verified using **AMD Vivado 2023.2** for the **Artix-7 FPGA** platform.

---

# Key Features

- Complete UART Protocol Implementation
- Modular VHDL Design
- Baud Rate Generator
- UART Transmitter
- UART Receiver
- Top-Level Integration
- Functional Simulation
- RTL Analysis
- FPGA-Oriented Design

---

# Development Environment

| Parameter | Details |
|------------|----------------|
| Language | VHDL |
| IDE | AMD Vivado 2023.2 |
| FPGA Family | Artix-7 |
| Device | XC7A35T |
| Design Methodology | RTL Design |

---

# Repository Structure

```
UART-Protocol-VHDL
│
├── baud_generator.vhd
├── uart_tx.vhd
├── uart_rx.vhd
├── uart_top.vhd
├── uart_tb.vhd
│
├── UART_PROJECT_BLOCK_DIAGRAM.jpg
├── UART_RTL_Schematic.png
├── UART_Project_Hierarchy.png
├── UART_Implemented_Design.png
├── Simulation_Waveform.png
│
├── LICENSE
└── README.md
```

---

# System Block Diagram

<img src="UART_PROJECT_BLOCK_DIAGRAM.jpg" width="900">

---

# RTL Schematic

<img src="UART_RTL_Schematic.png" width="900">

---

# Functional Verification

The complete UART communication was verified using Behavioral Simulation.

| Test | Result |
|------|---------|
| Input Data | 0xAA |
| Received Data | 0xAA |
| Transmission | PASS |
| Reception | PASS |

<img src="Simulation_Waveform.png" width="900">

---

# Project Hierarchy

<img src="UART_Project_Hierarchy.png" width="900">

---

# Implemented Design

<img src="UART_Implemented_Design.png" width="900">

---

# Working Principle

1. The Baud Generator generates the baud tick.
2. UART Transmitter converts parallel data into serial format.
3. Serial data is transmitted over the TX line.
4. UART Receiver detects the Start Bit.
5. Incoming serial bits are sampled.
6. Received data is reconstructed into parallel format.
7. The `rx_done` signal indicates successful reception.

---

# Applications

- FPGA-Based Embedded Systems
- Digital Communication
- Serial Communication Interfaces
- Industrial Automation
- IoT Devices
- Microcontroller Communication
- Communication Protocol Design
- Embedded Hardware Development

---

# Future Enhancements

- Configurable Baud Rate
- Parity Bit Support
- Variable Stop Bits
- FIFO Buffer
- Interrupt Support
- Hardware Validation on FPGA Board

---

# Simulation Status

| Module | Status |
|---------|--------|
| Baud Generator | Completed |
| UART Transmitter | Completed |
| UART Receiver | Completed |
| Top Module | Completed |
| Functional Simulation | Passed |
| RTL Verification | Passed |

---

# Author

## Mohammad Rahil Khan

Electronics and Computer Engineering

---

# License

Licensed under the MIT License.
