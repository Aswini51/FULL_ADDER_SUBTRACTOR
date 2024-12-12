### NAME : G ASWINI
### REG.NO. : 24000247
### EXPERIMRNT 4 :  FULL ADDDER AND SUBTRACTOR.

Implementation-of-Full-Adder-and-Full-subtractor-circuit

# AIM :

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

# EQUIPMENTS REQUIRED : 

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

# TRUTH TABLE :

![Screenshot 2024-12-12 162848](https://github.com/user-attachments/assets/8329359c-2106-4357-b29e-e70f96801406)

# PROCEDURE :

1. Type the program in Quartus software.
 2. Compile and run the program.
 3. Generate the RTL schematic and save the logic diagram.
 4. Create nodes for inputs and outputs to generate the timing diagram.
 5. For different input combinations generate the timing diagram

# PROGRAM :

![Screenshot 2024-12-12 162906](https://github.com/user-attachments/assets/28725590-a3ca-4ffe-8a16-f05dd658ede5)

# RTL :

![Screenshot 2024-12-12 162923](https://github.com/user-attachments/assets/27bffadd-0b13-4b50-ac6b-656bac79706c)

# OUTPUT TIMING WAVEFORM :

![Screenshot 2024-12-12 162939](https://github.com/user-attachments/assets/ef9ac386-ad66-48ef-9685-30005dbd1f91)

# RESULT :

 Full adder and subtractor circuit is studied and its truth table is verified in Quartus
 using Verilog programming.
