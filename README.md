### NAME : RABI BASKAR PRABURAJAN 
### REGISTER NUMBER: 24001812 
### EXPERIMENT 4 : FULL ADDER SUBTRACTOR



## AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

## EQUIPMENTS REQUIRED: 

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

## FULL ADDER AND FULL SUBTRACTOR 

## FULL ADDER 

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

## FULL SUBTRACTOR 

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

## PROCEDURE :

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for input and output to generate the timing diagram.

5.For different input combinations generate the timing diagram.

## PROGRAM :
![WhatsApp Image 2024-12-02 at 14 21 51_81c3046a](https://github.com/user-attachments/assets/8cf6fd5b-08f8-4d64-a463-21d01223e11e)

## TRUTHTABLE :
![WhatsApp Image 2024-12-02 at 14 23 05_ff856156](https://github.com/user-attachments/assets/ad627c61-c1d5-4df6-aee5-a308bf4b3f8b)

## RTL OUTPUT :
![WhatsApp Image 2024-12-02 at 14 24 20_094731fe](https://github.com/user-attachments/assets/599bc305-2d31-4f87-ae98-8ddd84b647f1)

## OUTPUT WAVEFORM :
![WhatsApp Image 2024-12-02 at 14 25 35_6dbad63d](https://github.com/user-attachments/assets/ee450374-73b3-41db-8b57-c11d2aed005f)

## RESULT :
   Thus the Full adder and Full subtractor circuits are designed and the truthtable is verified using quartus software.










