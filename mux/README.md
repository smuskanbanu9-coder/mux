# 4-to-1 Multiplexer Design using Verilog

## Overview
This project implements a 4-to-1 Multiplexer (MUX) using Verilog HDL.
A multiplexer is a combinational circuit that selects one input from multiple
inputs and forwards it to a single output based on select lines.

## Features
- 4 input lines
- 2 select lines
- 1 output line
- Combinational logic implementation
- Verified using a testbench simulation

## Block Diagram
    I0 ──┐
    I1 ──┤
    I2 ──┤──> MUX ───> Y
    I3 ──┘
         ↑
      Select Lines
        S1 S0
## Truth Table

| S1 | S0 | Output |
|----|----|--------|
| 0  | 0  | I0     |
| 0  | 1  | I1     |
| 1  | 0  | I2     |
| 1  | 1  | I3     |

## Tools Used
- Verilog HDL
- Icarus Verilog / ModelSim
- GTKWave

## Simulation
The design is verified using a testbench that checks all possible select
conditions.

## Author
Your Name