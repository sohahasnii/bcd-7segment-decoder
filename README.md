Binary to 7-Segment Decoder using Verilog

📌 Project Overview

This project implements a Binary-to-7-Segment Decoder using Verilog HDL. The circuit converts a 4-bit binary input into the corresponding output pattern required to display decimal digits from 0 to 9 on a seven-segment display.

The project demonstrates basic combinational logic design, Verilog coding, simulation, and digital circuit verification.

🎯 Objectives

- Design a binary-to-7-segment decoder using Verilog HDL.
- Understand combinational logic and conditional statements.
- Generate segment patterns for decimal digits.
- Verify the design using a Verilog testbench.
- Observe and analyze simulation waveforms using Vivado.

⚙️ Tools Used

- HDL: Verilog
- Design and Simulation: Xilinx Vivado
- Simulator: Vivado XSim
- Implementation Type: Combinational Logic Circuit

🧠 Working Principle

The decoder accepts a 4-bit binary input "A", representing values from 0 to 15, and generates seven outputs corresponding to segments "a" through "g".

Each output determines whether a particular segment is ON or OFF.

Binary Input| Decimal Digit| Display
0000| 0| 0
0001| 1| 1
0010| 2| 2
0011| 3| 3
0100| 4| 4
0101| 5| 5
0110| 6| 6
0111| 7| 7
1000| 8| 8
1001| 9| 9

Inputs from 10 to 15 can be assigned blank or other patterns depending on the design.

Note: The output patterns depend on whether the display is common-anode or common-cathode and on the order of the segment bits.



