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
Half adder:
module ex3(a,b,sum,carry);
input a,b;
output sum,carry;
assign sum=a^b;
assign carry=a&b;
endmodule 

Full adder:
module ex31(a,b,cin,sum,carry);
input a,b,cin;
output sum,carry;
assign sum=a^b^cin;
assign carry=(a&b)|((a^b)&cin);
endmodule

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: SHANMUGAKARTHIK G
RegisterNumber: 212223220105 
*/
Logic symbol & Truthtable
RTL realization

### Output:
### RTL
Half adder:
![image](https://github.com/Shanmugakarthik05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149762972/a39df7d0-5f2a-418e-91f2-3864b90ff290)

Full adder:
![image](https://github.com/Shanmugakarthik05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149762972/4dc22acb-c948-4e4d-8366-9a033c9bbc8d)

### TIMING DIAGRAM
Half adder:
![image](https://github.com/Shanmugakarthik05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149762972/afc62537-a0d6-4af9-bada-c892eab03805)

Full adder:
![image](https://github.com/Shanmugakarthik05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149762972/f3b4ba97-055e-46e7-84c0-06db7bc80d08)


### TRUTH TABLE 
Half adder:
![image](https://github.com/Shanmugakarthik05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149762972/cf65abcf-546e-4748-b41b-edf7a0c752d2)

Full adder:
![image](https://github.com/Shanmugakarthik05/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149762972/ea44ac95-ce4c-4f7c-ba9d-9d492553d32f)


### Result:
Thus the half adder and full adder circuit are designed and the truth table for half adder and full adder are verified.
