# 16-bit-Carry-Save-Multiplier-VHDL-Implementation
This repository contains the VHDL implementation of a 16-bit unsigned binary multiplier based on the "pen-and-paper" multiplication method, optimized using the carry-save technique. The project includes the design, simulation, and synthesis of the multiplier, along with detailed timing and power analysis. The multiplier is designed to efficiently compute the product of two 16-bit binary numbers, leveraging the carry-save adder to reduce propagation delays and improve performance.

Key features of the project:

    VHDL Implementation: The multiplier is implemented in VHDL, with modular components such as registers, adders, and carry-save units.

    Simulation and Testing: Includes a comprehensive test bench for behavioral simulation, ensuring correct functionality across all possible input combinations.

    Synthesis and Timing Analysis: The design is synthesized for an FPGA target (XC7Z020CLG400-3), with detailed post-synthesis timing analysis to evaluate performance under different clock constraints.

    Power and Frequency Analysis: The project includes power consumption and maximum operating frequency analysis for two clock configurations (12 ns and 25 ns), providing insights into the trade-offs between speed and energy efficiency.

This project is ideal for students and professionals interested in digital design, FPGA implementation, and VHDL programming. The repository includes all necessary files, including VHDL code, test benches, and synthesis reports, making it easy to replicate and extend the design.
