Implementation-of-Full-subtractor-circuit

AIM:
To design a  Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime

 Full Subtractor

Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.
<img width="940" height="407" alt="image" src="https://github.com/user-attachments/assets/03f20bfe-5793-4848-9995-5ad45320fed4" />
 
Diff = A ⊕ B ⊕ Bin
Borrow out = A'Bin + A'B + BBin
Truthtable
Procedure
Write the detailed procedure here
Program:
/* Program to design  a full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:R.AISHWARYA
RegisterNumber: 25017062
RTL Schematic
Output Timing Waveform
Result: Thus, the  Full Subtractor circuit  is  designed and the truth tables is verified using Quartus software.
