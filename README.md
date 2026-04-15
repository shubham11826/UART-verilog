# UART Design using Verilog

## Overview
This project implements a Universal Asynchronous Receiver Transmitter (UART) using Verilog HDL. The design includes transmitter, receiver, baud rate generator and testbench for simulation.
The design includes UART transmitter and receiver modules, followed by synthesis, gate-level verification, clock tree synthesis, and layout generation.

## Features
- UART Transmitter and Receiver Design
- RTL Simulation and Verification
- Gate-Level Netlist Generation
- Post-Synthesis Simulation
- Clock Tree Synthesis (CTS)
- Physical Layout Design

## Tools Used
- Verilog HDL
- Cadence Virtuoso
- Vivado Simulator
  

## Block Diagram
UART consists of:
- Baud Rate Generator
- Transmitter Module
- Receiver Module

 ## Project Structure
UART-Protocol/
│── rtl/
│── testbench/
│── synthesis/
│   ├── netlist/
│   ├── reports/
│   └── images/
│── layout/
│   ├── images/
│   ├── cts/
│   │   ├── reports/
│── README.md

## Design Flow
RTL → Synthesis → Floorplanning → Placement → Clock Tree Synthesis → Routing → Layout

## Simulation Result
The waveform verifies correct UART transmission and reception of data bits including start and stop bits.

## Clock Tree Synthesis (CTS)
Clock Tree Synthesis was performed to distribute the clock signal efficiently across the design.

## Highlights:
- Floorplanning and placement completed
- Routing performed
- Basic design rule checks considered

  ## Synthesis & Timing Reports
- Area and timing analyzed
- Setup and hold constraints verified

## Files
- uart_tx.v → UART transmitter
- uart_rx.v → UART receiver
- baud_rate_gen.v → Baud rate generator
- uart_tb.v → Testbench
  
## Conclusion
This project demonstrates a complete digital design flow from RTL to layout.

## Author
SHUBHAM KUMAR
