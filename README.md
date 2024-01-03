## Ex:03 Implementation of Half Adder and Full Adder circuit
Implementation-of-Half-Adder-and-Full-Adder-circuit
## AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
## Theory
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
### Program:

### Half Adder
![Screenshot 2024-01-03 174140](https://github.com/yoganand12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155515519/73277007-b156-4b92-a7b9-7b6564074602)


### Full Adder
![Screenshot 2024-01-03 174150](https://github.com/yoganand12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155515519/9eaf028d-9df4-4dfc-9a25-fbaf7464de69)



Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
## Logic symbol 

### Half Adder


![Screenshot 2024-01-03 174210](https://github.com/yoganand12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155515519/d5c09dd3-3c3e-4ae8-acbf-4dc57a3caa9a)

### Full Adder
![Screenshot 2024-01-03 174219](https://github.com/yoganand12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155515519/86a061e6-4bef-4289-92e4-1aa6dc6d4bd2)


## Truthtable

### Half Adder

![Screenshot 2024-01-03 174229](https://github.com/yoganand12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155515519/0ad0d84c-86e5-49f6-a59a-6d95afbdd38c)


### Full Adder

![Screenshot 2024-01-03 174244](https://github.com/yoganand12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155515519/12656811-5439-45a0-8728-0d0c26ea79ca)

## RTL realization

### Half Adder

![Screenshot 2024-01-03 174254](https://github.com/yoganand12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155515519/86783fee-22d6-4845-b4d6-cdc5373d2a28)


 ### Full Adder

 ![Screenshot 2024-01-03 174305](https://github.com/yoganand12/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/155515519/6b953b50-a854-4f75-8d92-a41e24e3aa2d)


### Result:

To design a half adder and full adder circuit and verify its truth table in quartus using verilog programming.
