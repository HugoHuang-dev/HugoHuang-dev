# Sunmingyin Huang (Hugo)

Electrical Engineering undergraduate focused on **FPGA, RTL design, and digital system architecture**.

My recent work focuses on taking FPGA designs through the complete engineering flow:

**RTL architecture → simulation → synthesis → static timing analysis → implementation → board-level verification**

## Selected Projects

### FPGA DDR3-Buffered Gigabit Ethernet Data Acquisition and Streaming System

Multi-clock Artix-7 RTL system featuring **CDC, AXI4/MIG, DDR3 ring buffering, concurrent memory access, flow control, RGMII/UDP streaming, timing-constraint debugging, and hardware validation**.

**Highlights:** 397.845 Mb/s sustained UDP payload throughput over a 1-hour hardware run.

[View Project](https://github.com/HugoHuang-dev/fpga-ddr3-gigabit-ethernet-daq)

### FPGA Multi-Source Data Acquisition and Communication System

Synchronous Artix-7 RTL system featuring **FSM-based control, dual-FIFO buffering, XADC acquisition, UART/CRC-16 communication, and shared-I²C resource arbitration**.

**Highlights:** 2-hour / 7.20M-record hardware validation with zero CRC errors, sequence gaps, or dropped samples.

[View Project](https://github.com/HugoHuang-dev/fpga-multi-protocol-daq)

## Technical Focus

**Digital Design:** Verilog RTL, FSMs, CDC, FIFOs, flow control, clock/reset design  
**Memory & Interfaces:** AXI4/MIG, DDR3, RGMII, UDP, UART, I²C  
**EDA & Verification:** Vivado, ModelSim, synthesis, static timing analysis, timing constraints, ILA
