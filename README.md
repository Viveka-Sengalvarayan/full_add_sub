# FULL_ADDER_SUBTRACTOR

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

<img width="1920" height="1140" alt="Screenshot 2025-11-23 104032" src="https://github.com/user-attachments/assets/2595b50b-e21c-4d82-a28d-d26320fe2186" />

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.



<img width="1920" height="1140" alt="Screenshot 2025-11-23 105055" src="https://github.com/user-attachments/assets/2e67307f-e59e-4544-bab1-0a55f37ab657" />

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


Developed by: viveka 

RegisterNumber:25016820
*/

**RTL Schematic**

**Output Timing Waveform**
full adder 

<img width="1911" height="1151" alt="Screenshot 2025-11-23 104330" src="https://github.com/user-attachments/assets/607f578c-714e-4b8b-bc30-73d942d33034" />

full subtractor 


<img width="1911" height="1151" alt="Screenshot 2025-11-23 105301" src="https://github.com/user-attachments/assets/7e09ae4b-ea29-4109-ad64-0903c2f263a5" />



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.

