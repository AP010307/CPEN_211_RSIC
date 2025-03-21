# CPEN_211_RSIC
## Overview
This project is 3 labs combined into one project for CPEN 211, where we designed a  reduced set instruction computer (RISC) machine using SystemVerilog and ARM assembly on a De1-SoC board. The RISC machine is capable of performing basic arithmetic operations and memory operations.

## Introduction
The project was divided into two parts: the SystemVerilog part and the ARM assembly part. The SystemVerilog part was to design the RISC machine using a finite state machine (FSM) and the ARM assembly part was to write a program that runs on the RISC machine. The RISC machine was designed to have a 16-bit data bus, 16-bit address bus, 16-bit registers, and 16-bit memory. The machine was capable of performing basic arithmetic operations such as addition, subtraction, multiplication, and division. It was also capable of performing memory operations such as load and store.

## Objective
The objective conveyed the following requirements:
- **Datapath**
  - A register file containing 8 locations with 16-bit registers.
  - A 16-bit ALU capable of performing addition, subtraction, multiplication, and division.
- **Finite state machine controller**
  - A finite state machine that controls the datapath.
  - The FSM should be able to perform the following operations:
    - Load a value from memory to a register.
    - Store a value from a register to memory.
    - Perform arithmetic operations.
- **Memory input and output**
    - A 16-bit memory that can store 256 16-bit values.
    - The memory should be able to read and write values.
