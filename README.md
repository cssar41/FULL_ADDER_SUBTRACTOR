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



**Full Subtractor**


![image](https://github.com/23004205/FULL_ADDER_SUBTRACTOR/assets/138971114/fddd5b27-d8f5-4ee6-be4e-5ecab782a082)

```
**RTL Schematic**

**Full Adder:**

![image](https://github.com/23004205/FULL_ADDER_SUBTRACTOR/assets/138971114/0648c588-7528-4d30-a5da-56a67085ec7a)

**Full Subtractor**

![image](https://github.com/23004205/FULL_ADDER_SUBTRACTOR/assets/138971114/ec01c5d8-d8fa-4d68-b6a8-37fbc38b9930)


**Output Timing Waveform**


**Full Adder:**

![image](https://github.com/23004205/FULL_ADDER_SUBTRACTOR/assets/138971114/c788a1ba-3cd7-4040-a945-dd39d67ee7a3)


**Full Subtractor**


![image](https://github.com/23004205/FULL_ADDER_SUBTRACTOR/assets/138971114/c9fb0fae-edbe-459d-a32e-10ababae97a5)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



