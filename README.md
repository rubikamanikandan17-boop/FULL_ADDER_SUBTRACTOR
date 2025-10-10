z# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin
## circut diagram 
https://github.com/rubikamanikandan17-boop/BOOLEAN_FUNCTION_MINIMIZATION/tree/main
## output
![WhatsApp Image 2025-10-09 at 19 01 07_55965b7a](https://github.com/user-attachments/assets/fabf9236-0d4f-4293-b1f1-9bcc8349af89)

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)
# truth table
#![WhatsApp Image 2025-10-10 at 13 04 39_994db012](https://github.com/user-attachments/assets/7a06ee5f-94e2-4616-8659-1b0c25e03193)
 

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin
## circut diagram 
![WhatsApp Image 2025-10-09 at 19 01 08_bc1ffb1c](https://github.com/user-attachments/assets/858c9f5f-983f-4858-ac48-554d7c0a8268)

## output
![WhatsApp Image 2025-10-09 at 19 01 08_81efda95](https://github.com/user-attachments/assets/9b1969cd-c157-41ef-8d52-a8b8c7263b96)

**Truthtable**
![WhatsApp Image 2025-10-10 at 13 04 54_da5bdb45](https://github.com/user-attachments/assets/30d13846-30be-45c4-a141-4c8cf979a0bd)

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**

**Output Timing Waveform**

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



