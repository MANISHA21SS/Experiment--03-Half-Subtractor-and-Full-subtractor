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



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: MANISHA SELVAKUMARI S S
RegisterNumber: 23012275 
*/
Code:
Half subtractor:
![halfsubtractor code](https://github.com/MANISHA21SS/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474298/73608cde-881c-43a6-9fe5-9fe0167572e3)
Full subtractor:
![full subtractor code](https://github.com/MANISHA21SS/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474298/a794ffd9-41cb-42e8-94da-db7f9fa51ddc)

## Output:
Half subtractor:
![halfsubtractor output](https://github.com/MANISHA21SS/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474298/67676758-dd84-47da-95fa-23f29aa99d26)
Full subtractor:
![fullsubtractor output](https://github.com/MANISHA21SS/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474298/393d2fb2-6add-441a-9d7b-b2e29f8e6057)


## Truthtable
![halfsubtractor truthtable](https://github.com/MANISHA21SS/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474298/3fa845d8-d3a6-459f-b2eb-5adf6b0d06f5)

![fullsubtractor truthtable](https://github.com/MANISHA21SS/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474298/d4560f61-4048-4c79-a232-888edb49d655)

##  RTL realization
Half subtractor:
![halfsubtractor rtl diagram](https://github.com/MANISHA21SS/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474298/82cd8a54-2e88-4673-8c12-b8055db43568)
Full subtractor:
![full subtractor rtl diagram](https://github.com/MANISHA21SS/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474298/a4e05dff-59a3-4e0e-9704-200e556e211e)

## Timing diagram 
Half subtractor:
![halfsubtractor timing diagram](https://github.com/MANISHA21SS/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474298/512b3087-7643-47fc-8bbf-46075c401587)
Full subtractor:
![fullsubtractor timing diagram](https://github.com/MANISHA21SS/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474298/575b7f28-e786-4911-9a63-87a16b77ae75)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
