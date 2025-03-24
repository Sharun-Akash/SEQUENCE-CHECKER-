# SEQUENCE-CHECKER-
This project implements a Sequence Detector on an FPGA using Verilog. The Sequence Detector is designed to recognize specific bit sequences in a continuous input stream.
Key Features:
Overlapping Sequence Detection: Detects sequences where the pattern can overlap in consecutive inputs.

Non-overlapping Sequence Detection: Detects sequences where each occurrence of the pattern is separate.

Key Modules:
FSM (Finite State Machine): Used to model the state transitions based on input bits and detect when the sequence occurs.

Clock Divider: Divides the system clock for timing control, ensuring proper sequence detection based on slower input signal frequencies.

Testbench: A Verilog testbench is used to simulate the functionality of the sequence detector, ensuring correctness before hardware implementation on the FPGA.

Tools Used:
Xilinx Vivado for FPGA development and simulation.

ZedBoard FPGA board for hardware implementation.
