
# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/00000000
Logic symbol & Truthtable
RTL realization

### Output:
### RTL
### TIMING DIAGRAM
![Screenshot 2023-11-26 142848](https://github.com/Mohanraj2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152195759/2cb50f9f-2185-4657-b929-3b610c734ed7)
![Screenshot 2023-11-26 142029](https://github.com/Mohanraj2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152195759/e7ff9cca-8b80-45f6-9f73-48a4a58ddfea)


### TRUTH TABLE 
![WhatsApp Image 2023-12-07 at 15 55 59_9aa26e09](https://github.com/Mohanraj2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152195759/ce0a515f-c8c9-4823-baf5-a28af605a548)
![WhatsApp Image 2023-12-07 at 15 56 50_eb552598](https://github.com/Mohanraj2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152195759/57d3f37d-989e-4353-bf5f-35441c328496)

### Result:
0000000000000000000000
