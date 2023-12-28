# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure

Step 1:
Use module program name(input,output)to start the verilog program

Step 2:
Assign inputs and outputs

Step 3:
End the verilog program using keyword endmodule


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: Harevasu S
RegisterNumber: 23004355 
*/

# CODE:

## HALF SUBTRACTOR:

![code](https://github.com/Harevasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147985044/eb18ede1-071a-45ea-aa69-3e84ebcc9026)



## FULL SUBTRACTOR:

![code](https://github.com/Harevasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147985044/bf1a672d-8a5d-4be1-9063-e09d3263f267)


# TRUTH TABLE:

## HALF SUBTRACTOR:

![truth table](https://github.com/Harevasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147985044/529c9555-3c3f-43cd-ba74-e88b44682282)


## FULL SUBTRACTOR:

![truth table](https://github.com/Harevasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147985044/7b4c8e0e-58f0-4fd4-86a6-dcd116e9d14d)


#  RTL DIAGRAM:

## HALF SUBTRACTOR:

![RTL](https://github.com/Harevasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147985044/99ae69ed-a27a-460f-b1bb-340ab0dca40c)


## FULL SUBTRACTOR:

![RTL](https://github.com/Harevasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147985044/69e8da8a-ab13-41fb-a9e3-1444bb26323a)


# TIMING DIAGRAM:


## HALF SUBTRACTOR:

![output](https://github.com/Harevasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147985044/502d8234-d714-4aa2-a690-8be7fd719b77)


## FULL SUBTRACTOR:

![output](https://github.com/Harevasu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147985044/35449a66-e255-443a-92d4-1fd9d2b6cb4e)



# Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
