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

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
```
Developed by: singamala venkata sai kumar reddy
RegisterNumber:212223230208
```

**Full Adder:**

![image](https://github.com/23004205/FULL_ADDER_SUBTRACTOR/assets/138971114/b0e7c4f5-0b74-4832-ad89-c0bcd1cb2d0c)



**Full Subtractor**


![image](https://github.com/23004205/FULL_ADDER_SUBTRACTOR/assets/138971114/6d5473f3-0390-4c11-a271-67eafef62a0f)



**RTL Schematic**

**Full Adder:**

![exp 4 rtl schematic fadder](https://github.com/23003250/FULL_ADDER_SUBTRACTOR/assets/139331462/a8fec4ef-013e-4ab6-9ece-32edb9b7a839)

**Full Subtractor**

![exp 4 rtl schematic fsubtractor](https://github.com/23003250/FULL_ADDER_SUBTRACTOR/assets/139331462/38de2167-852a-45e7-ba22-09af1211a59d)

**Output Timing Waveform**

**Full Adder:**

![exp 4 waveform fadder](https://github.com/23003250/FULL_ADDER_SUBTRACTOR/assets/139331462/9ac232ab-b295-4ab7-8afe-671951daa081)


**Full Subtractor**

![exp 4 waveform fsubtractor](https://github.com/23003250/FULL_ADDER_SUBTRACTOR/assets/139331462/82f281e0-b870-409c-be34-884f15c22d5b)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.

