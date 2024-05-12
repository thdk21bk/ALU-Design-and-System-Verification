# ALU Design and System Verification

## Overview
This project presents an 8-bit Arithmetic Logic Unit (ALU) capable of performing arithmetic and bitwise operations. Designed and implemented using Verilog, along with Cadence tools for synthesis and system verification, the ALU supports a comprehensive functional and structural verification process, ensuring robust performance across various computational tasks.

## Features
- **Operations Supported**: Addition, subtraction, bitwise AND, and bitwise OR.
- **Functional Equivalence**: Utilized Logic Equivalence Checking (LEC) to validate the synthesized netlist against the original RTL, ensuring integrity and correctness.
- **Simulation**: Extensive simulation tests to verify all operations under diverse scenarios and input conditions.

## Interface
- **Inputs**:
  - `Input1` & `Input2`: 8-bit inputs for arithmetic and logical operations.
  - `Control`: 4-bit input to select the operation.
- **Outputs**:
  - `Output`: 8-bit output presenting the result of the computed operation.
  - `Zero`: Single bit output, set to 1 if the result is zero.
