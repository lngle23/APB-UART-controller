# APB-based UART Controller

A synthesizable APB-compliant UART controller implemented in Verilog, designed for SoC integration and digital design practice.

## Features
- APB slave interface for register-based control, status, and data access
- UART transmitter and receiver with configurable baud rate
- Receiver supports no parity, even parity, and odd parity
- Framing error, fake start bit, and overflow detection
- Modular RTL design with FSM-based control logic

## Design Overview
The design integrates an APB interface with a UART core, allowing a processor to configure and communicate with the UART through memory-mapped registers.  
All modules are written in synthesizable Verilog and organized for clarity and reuse.

## Tools
- Verilog HDL  
- ModelSim / Icarus Verilog (simulation)  
- GTKWave (waveform analysis)

## Status
Functional RTL design completed. Suitable for learning APB bus protocol and UART implementation in SoC environments.

