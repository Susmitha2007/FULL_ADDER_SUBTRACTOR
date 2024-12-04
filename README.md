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


**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.



Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**


![Screenshot 2024-12-04 135237](https://github.com/user-attachments/assets/bcba0f3d-8557-41a8-8ac8-f490e8a93b2f)


![Screenshot 2024-12-04 135250](https://github.com/user-attachments/assets/32e7cf5b-c9fe-4c2b-85c6-0ef85026ca26)


**Procedure**
1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:Nara Guna Susmitha RegisterNumber:24010204

![Screenshot 2024-12-02 104602](https://github.com/user-attachments/assets/e14be0f1-ebd6-4350-a615-fac1aa55379a)

![Screenshot 2024-12-02 105011](https://github.com/user-attachments/assets/983ce361-3091-4a23-9688-15f7d2997bd5)

*/

**RTL Schematic**
![Screenshot 2024-12-02 104244](https://github.com/user-attachments/assets/13a6bacb-70a1-4962-811a-c15b402774de)
![Screenshot 2024-12-02 104940](https://github.com/user-attachments/assets/14915fce-64eb-4f7d-96ce-809b66200060)


**Output Timing Waveform**
![Screenshot 2024-12-02 104007](https://github.com/user-attachments/assets/e50238cd-859f-4ec5-9473-9a59c8b4aaf5)
![Screenshot 2024-12-02 104028](https://github.com/user-attachments/assets/08ea8511-eec5-48d6-b0f4-89b364d0ebc9)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



