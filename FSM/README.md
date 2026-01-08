Sequence Detector (101) - Moore FSM (Overlapping)
This repository contains a Verilog implementation of a Moore State Machine that detects the sequence 101. 
The design supports overlapping sequences, meaning the last bit of a detected sequence can serve as the first bit of the next sequence.

FSM Characteristics
Type: Moore Machine (Output depends only on the current state).
Sequence: 101.
Overlap: Enabled (e.g., 10101 will trigger the output twice).
Reset: Asynchronous, active high.
