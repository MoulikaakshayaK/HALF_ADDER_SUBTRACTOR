# EXP3:HALF_ADDER_SUBTRACTOR

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

![tt A](https://github.com/user-attachments/assets/2ab038b3-258e-4f94-988a-583354318107)

![tt B](https://github.com/user-attachments/assets/532b65c6-d9a9-4645-b3a9-eb884bff1aee)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

![halfadder code](https://github.com/user-attachments/assets/ec86d522-7f85-4b1d-91d3-035abd5c7158)

![halfsubtractor code](https://github.com/user-attachments/assets/8840e71a-6fbb-4feb-8e8a-dd7ee48dde23)



**RTL Schematic**

![halfadder diagram](https://github.com/user-attachments/assets/15690a25-1bf3-45ee-ab4b-c42cf314fe45)

![halfsubtractor diagram](https://github.com/user-attachments/assets/fb97a5dd-db94-4f5b-81f6-bac658d2247a)



**Output/TIMING Waveform**

![halfadder waveform](https://github.com/user-attachments/assets/eff8bf6f-4c44-462e-b968-29647dbea0dd)

![halfsubtractor waveform](https://github.com/user-attachments/assets/bcb1f629-8a47-4aa3-a1b2-ca46c233c68a)



**Result:**

Thus the half adder and half subtractor is studied and the truth table,logic diagram ,waveform is verified.
