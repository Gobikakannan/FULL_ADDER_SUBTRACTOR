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
### Full Adder:
![exp4 table add](https://github.com/Gobikakannan/FULL_ADDER_SUBTRACTOR/assets/163496346/e2f51537-bb3f-4f4e-babf-cae78102d327)
### Full Subtractor:
![exp4 table sub](https://github.com/Gobikakannan/FULL_ADDER_SUBTRACTOR/assets/163496346/acc3ff81-1e04-445d-af51-a6face6abde8)

### Procedure:
![procedure](https://github.com/Gobikakannan/FULL_ADDER_SUBTRACTOR/assets/163496346/49f41f2e-38a1-442a-b570-0397506ec359)



**Program:**

![exp4 code add](https://github.com/Gobikakannan/FULL_ADDER_SUBTRACTOR/assets/163496346/dd4855f7-1e40-49f7-91a8-32b0bcf86ce0)
### Full Subtractor:
![exp4 code sub](https://github.com/Gobikakannan/FULL_ADDER_SUBTRACTOR/assets/163496346/bf0c6d59-b6ed-4216-a36d-ffde91647c55)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:Gobika K
RegisterNumber:212222050013
*/

**RTL Schematic**
![exp4 rtl add](https://github.com/Gobikakannan/FULL_ADDER_SUBTRACTOR/assets/163496346/31b3216b-0af3-484f-89e1-f7a895dfc651)
### Full Subtractor:
![exp4 rtl sub](https://github.com/Gobikakannan/FULL_ADDER_SUBTRACTOR/assets/163496346/707805ca-3569-458c-8036-63a2d60b5b4d)

**Output Timing Waveform**
![exp4 output add](https://github.com/Gobikakannan/FULL_ADDER_SUBTRACTOR/assets/163496346/64f1ced3-7ff6-4858-9712-e86151142328)
![exp4 output sub](https://github.com/Gobikakannan/FULL_ADDER_SUBTRACTOR/assets/163496346/2afb681f-b9f8-4e6b-b161-13791c5602e1)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



