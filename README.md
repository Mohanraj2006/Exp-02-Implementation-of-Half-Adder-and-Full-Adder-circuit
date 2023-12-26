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
## Half adder

![Screenshot 2023-12-25 205754](https://github.com/Mohanraj2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152195759/f122a9ba-de07-4040-a506-ef0f6513f08b)

##Full adder

![Screenshot 2023-12-25 205758](https://github.com/Mohanraj2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152195759/efb12dc5-02df-464f-ad37-7ddeaa2111c1)

/*
Program to design a half adder and full adder circuit and verify its truth table in quarts using Verilog programming.

Developed by: Mohan raj.C

RegisterNumber: 23014008

*/00000000
 

### Output:
### RTL REALIZATION
## Half adder

![Screenshot 2023-12-27 000921](https://github.com/Mohanraj2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152195759/c6a626d7-3ec1-4405-af34-b8d1213f1128)


##Full adder

![Screenshot 2023-12-27 000928](https://github.com/Mohanraj2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152195759/b089655f-caa6-449a-b898-c511290f0672)


### TRUTH TABLE 
 ### Half adder

![Screenshot 2023-12-27 000122](https://github.com/Mohanraj2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152195759/04369a54-a696-4002-8ab9-de2e5812fff8)

##Full adder

![Screenshot 2023-12-27 000128](https://github.com/Mohanraj2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152195759/c577f3f6-97eb-45c1-b613-0c63bc449d4e)

 ##Timing diagram
 ### Half adder

![Screenshot 2023-11-26 142848](https://github.com/Mohanraj2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152195759/2cb50f9f-2185-4657-b929-3b610c734ed7)

##Full adder

![Screenshot 2023-11-26 142029](https://github.com/Mohanraj2006/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/152195759/e7ff9cca-8b80-45f6-9f73-48a4a58ddfea)


### Result:
Thus a Half Adder and Full Adder is designed and its truthtables are verified in Quartus using Verilog programming
