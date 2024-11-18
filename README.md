# EXP 3 : HALF ADDER AND SUBTRACTOR
## NAME : RUSHMITHA R
## REGISTRATION NUMBER : 24006587

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

HALF ADDER :
![HALF ADD TT](https://github.com/user-attachments/assets/664b723c-b6ad-4394-8bc0-57df07e4e1ed)


HALF SUBTRACTOR :
![HALF SUB TT](https://github.com/user-attachments/assets/48bc6674-4e1c-43a5-baa4-fab16466284c)

**Code**

HALF ADDER :
![half adder code](https://github.com/user-attachments/assets/3f2d2318-04d2-48d1-b9fb-0c13f995ddcb)


HALF SUBTRACTOR :
![half subtractor code](https://github.com/user-attachments/assets/fe4fa652-03dd-42d1-848e-0ffff94eb703)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber:*/

**RTL Schematic**

HALF ADDER :
![half adder circuit ](https://github.com/user-attachments/assets/eec6886f-e568-4660-b856-f52e05af0737)

HALF SUBTRACTOR :
![half subtractor logic](https://github.com/user-attachments/assets/7e758a05-50bc-4f75-9e6b-4cd0f67d6f04)

**Output/TIMING Waveform**

HALF ADDER :
![Half adder waveform](https://github.com/user-attachments/assets/bdebdc73-833b-4f39-b32e-97b614899a36)

HALF SUBTRACTOR :
![half subtractor waveform](https://github.com/user-attachments/assets/959d3d06-9ee6-49c7-bdc4-9e9e6fb058a1)


**Result:**
Thus a half adder and half subtractor circuit is designed and the truth table is verified in
Quartus using Verilog programming.

