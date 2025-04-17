# RISC-V RV32I Single-Cycle CPU

This repo contains a single-cycle CPU implementation in Verilog for the RISC-V RV32I subset.

## Structure
- `src/`: All Verilog modules
- `testbench/`: Testbenches for simulation
- `program.hex`: Machine code to be loaded into instruction memory

## Simulation
Run in ModelSim:
```bash
vlog src/*.v testbench/*.v
vsim work.CPU_tb
run 300
```
