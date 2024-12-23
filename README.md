# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It
 is fundamental to digital logic design and computer science, providing a mathematical
 framework for describing logical operations and expressions

![WhatsApp Image 2024-12-21 at 08 56 17_6e13c88f](https://github.com/user-attachments/assets/ec2a7e08-f4a2-49d3-8ac7-8ccada72777c)

![WhatsApp Image 2024-12-21 at 08 56 30_831696e9](https://github.com/user-attachments/assets/f6a739f8-84a8-4516-904c-509a6e5f6488)


**Logic Diagram**

![Screenshot (4)](https://github.com/user-attachments/assets/2b8e8e71-fb19-4f2b-b66b-3c7d90a1a3c0)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

i)
module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii)
module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule
 

Developed by:S.Dhamini

RegisterNumber:24002208


**RTL**

![WhatsApp Image 2024-12-21 at 17 40 03_69127280](https://github.com/user-attachments/assets/19c6a5c5-fbff-45ad-82ef-7ed7f8fc55bd)

![image](https://github.com/user-attachments/assets/2225ad10-e619-4e4f-acab-83f2288c34d8)



**Timing Diagram**

![WhatsApp Image 2024-12-21 at 17 40 47_99d4b512](https://github.com/user-attachments/assets/6049ddfd-2372-47c5-912b-57768f2fc18c)

![WhatsApp Image 2024-12-23 at 08 27 08_2cf88e01](https://github.com/user-attachments/assets/3e5ecc77-14fd-4766-bf40-7080eaa84c7f)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

