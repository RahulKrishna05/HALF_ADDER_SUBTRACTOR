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

Developed by:Rahul Krishna RegisterNumber:212223040162 */

**code**

**Half Adder**

![Screenshot 2024-04-03 100819](https://github.com/RahulKrishna05/HALF_ADDER_SUBTRACTOR/assets/162027231/7d66e181-098b-4ca9-85f1-2c695a631441)

**Half Subtractor**

![Screenshot 2024-04-03 100842](https://github.com/RahulKrishna05/HALF_ADDER_SUBTRACTOR/assets/162027231/a43c36e2-5f92-433b-8844-d3d352fea602)

**RTL Schematic**

**Half Adder**

![Screenshot 2024-04-03 100900](https://github.com/RahulKrishna05/HALF_ADDER_SUBTRACTOR/assets/162027231/e6e3e38a-ea00-42c7-b4d6-21af63c8ab24)

**Half Subtractor**

![Screenshot 2024-04-03 100917](https://github.com/RahulKrishna05/HALF_ADDER_SUBTRACTOR/assets/162027231/3a6ef3f4-0551-409d-8d68-5ca3b18290c5)

**Output/TIMING Waveform**

**Half Adder**

![Screenshot 2024-04-03 100934](https://github.com/RahulKrishna05/HALF_ADDER_SUBTRACTOR/assets/162027231/557e06fa-b607-4c4b-8b11-c35eadc45ae1)

**Half Subtractor**

![Screenshot 2024-04-03 100948](https://github.com/RahulKrishna05/HALF_ADDER_SUBTRACTOR/assets/162027231/09426a8e-22fa-4ddd-bd4c-211778a158e8)

**Result:**

Thus, a half adder and half subtractor circuit is designed to verify its truth table in Quartus using Verilog programming.
