
# Sunmingyin Huang (Hugo)

Electrical Engineering undergraduate focused on RTL design, digital verification, and FPGA/ASIC implementation.

My projects span multi-clock FPGA systems, memory built-in self-test, automated verification, and hardware validation. I focus on connecting RTL architecture with reproducible simulation, synthesis, timing analysis, and implementation results.

## Selected Projects

### [Project II — FPGA DDR3-Buffered Gigabit Ethernet DAQ](https://github.com/HugoHuang-dev/fpga-ddr3-gigabit-ethernet-daq)

Multi-clock Artix-7 system integrating asynchronous CDC, AXI4/MIG, DDR3 ring buffering, flow control, and RGMII/UDP streaming.

**Highlight:** 397.845 Mb/s sustained UDP payload throughput over a 1-hour hardware endurance run.

### [Project III — RTL MBIST with FPGA/ASIC Verification](https://github.com/HugoHuang-dev/rtl-mbist-fault-coverage)

March C− MBIST with independent transaction checking, automated fault injection, FPGA board validation, and Nangate45 ASIC synthesis, gate-level verification, and pre-placement timing analysis.

**Highlights:** All 2,048 defined single-fault instances detected across two simulators; ASIC synthesis mapped the controller to 264 standard cells.

### [Project I — FPGA Multi-Source Data Acquisition](https://github.com/HugoHuang-dev/fpga-multi-protocol-daq)

Artix-7 acquisition system featuring FSM-based control, dual-FIFO buffering, XADC sampling, UART/CRC-16 communication, and shared-I²C arbitration.

**Highlight:** 2-hour hardware validation covering approximately 7.20 million records with zero CRC errors, sequence gaps, or reported sample drops.

## Technical Focus

- **RTL & Architecture:** Verilog, SystemVerilog, FSMs, CDC, FIFOs, AXI4/MIG, DDR3, and digital interfaces.
- **Verification:** ModelSim, XSim, Icarus Verilog, Python automation, independent checking, fault injection, and gate-level regression.
- **Implementation & Timing:** Vivado, FPGA implementation, ILA, Yosys, OpenROAD/OpenSTA, standard-cell synthesis, and static timing analysis.
