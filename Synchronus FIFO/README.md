Synchronous FIFO Buffer (8x8)
This repository contains a synthesizable Synchronous FIFO (First-In-First-Out) buffer designed in Verilog.
The design serves as a hardware solution for handling data rate mismatches between a Fast Producer and a Slow Consumer within the same clock domain.

Architecture Features
Depth: 8 entries | Data Width: 8 bits.

Status Flags: Real-time generation of Full and Empty signals to prevent data overflow and underflow.

Handshaking: Implements backpressure logic using wr_en/full and rd_en/empty pairs.

Hardware Optimized: Uses pointer-based memory addressing. 
The memory array is not reset to optimize for ASIC Area and Power, adhering to industry standards where only control logic (pointers) is reset.

