### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**
module gates_exp1(a, b, c, d, e, x, y, z);
  input a, b;
  output c, d, e, x, y, z;

  assign c = a & b;   // AND gate
  assign d = a | b;   // OR gate
  assign e = a ^ b;   // XOR gate
  assign x = ~(a & b); // NAND gate
  assign y = ~(a | b); // NOR gate
  assign z = ~(a ^ b); // XNOR gate

endmodule

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by:P.Kabilan
 RegisterNumber: 24900859
 
**Logic symbol & Truthtable**
![WhatsApp Image 2024-12-05 at 18 36 15_c7d5310f](https://github.com/user-attachments/assets/039e1775-cd58-4528-b3fb-7e1d88297d83)


**RTL realization Output:** 
![Screenshot (2)](https://github.com/user-attachments/assets/eb58cb8f-5063-4cf5-9920-432207a066e0)


**RTL**
![Screenshot (1)](https://github.com/user-attachments/assets/7c228683-77e7-4c4c-8391-539302e96030)

**Result:**
Thus the basic logic gates are studied and verified.

