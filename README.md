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

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

![Screenshot 2024-12-23 103017](https://github.com/user-attachments/assets/616bd772-3288-4c45-a5cd-c3756759c25e)


**Procedure**

Write the detailed procedure here

**Program:**

![Screenshot 2024-12-23 103029](https://github.com/user-attachments/assets/e6a877e3-3376-4033-bb8f-a06489c55318)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**


![Screenshot 2024-12-21 103749](https://github.com/user-attachments/assets/925db6ad-dd3d-4532-8a4b-8fff5f4f8791)

![Screenshot 2024-12-21 103743](https://github.com/user-attachments/assets/9c27e372-e358-47f6-b312-d33451774e15)

**Output Timing Waveform**

![Screenshot 2024-12-21 103815](https://github.com/user-attachments/assets/f9be0e26-a25f-4c9f-977c-3087cf1ed5b8)


![Screenshot 2024-12-21 103804](https://github.com/user-attachments/assets/ae2b01ea-a5a3-4590-8bc6-5fa4c00cee6a)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



