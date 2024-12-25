# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

![image](https://github.com/user-attachments/assets/7f84451f-53c1-4854-a571-bf71bba15527)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Buvaneshwari.R

RegisterNumber:24900165.


module ex_2(a,b,c,d,w,x,y,z,f1,f2)
intput a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule


**RTL realization output**

![image](https://github.com/user-attachments/assets/a4cc08e1-c390-40a9-bcb3-9d7d05ff8c70)



**Timing Diagram**

![image](https://github.com/user-attachments/assets/01735ed8-ba28-4eb9-86da-ffc255e913e6)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

