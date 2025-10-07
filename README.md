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

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
<img width="915" height="531" alt="Screenshot 2025-10-07 131855" src="https://github.com/user-attachments/assets/f16d82f1-1897-4695-9060-1ba4353a7929" />
<img width="753" height="394" alt="Screenshot 2025-10-07 134251" src="https://github.com/user-attachments/assets/22545551-710a-45a3-bf30-3f8df9185969" />


**Output Timing Waveform**<img
<img width="1920" height="798" alt="Screenshot 2025-10-07 132140" src="https://github.com/user-attachments/assets/395641aa-1485-4b62-a884-5fee6829a35e" />
<img width="1912" height="749" alt="Screenshot 2025-10-07 134512" src="https://github.com/user-attachments/assets/d624dcd1-6774-45de-9fcb-919ebfdce2d7" />


**Result:**
this is verified by protus

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



