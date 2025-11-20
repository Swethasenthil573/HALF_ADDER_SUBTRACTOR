# HALF_ADDER_SUBTRACTOR

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

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
<img width="508" height="385" alt="Screenshot 2025-11-20 130251" src="https://github.com/user-attachments/assets/95137340-0fcf-46fc-a1e4-f54f65477217" />
<img width="719" height="331" alt="Screenshot 2025-11-20 130824" src="https://github.com/user-attachments/assets/4dacaf17-1ccf-42f2-bb55-7e59c3701656" />

Developed by:Sweths.S RegisterNumber:25017890

**RTL Schematic**
<img width="1579" height="812" alt="Screenshot 2025-11-20 130004" src="https://github.com/user-attachments/assets/1ad027db-8c38-4296-9d3b-e918d12a167b" />

<img width="1625" height="793" alt="Screenshot 2025-11-20 130627" src="https://github.com/user-attachments/assets/5c594c52-50bc-4964-ae98-43db0901469e" />

**Output/TIMING Waveform**

<img width="1686" height="818" alt="Screenshot 2025-11-20 130217" src="https://github.com/user-attachments/assets/54c208bb-abed-4d99-8fce-6c3d16eee577" />

<img width="1702" height="286" alt="Screenshot 2025-11-20 130804" src="https://github.com/user-attachments/assets/e7d46978-10b5-4074-8e37-72b8e32f143b" />

**Result:**
thus the given design implemented and verified using truth table
