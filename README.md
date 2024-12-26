# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
Developed by:porkodi B RegisterNumber:24900502*/


**RTL realization**
![Screenshot 2024-11-12 175420](https://github.com/user-attachments/assets/4e7914a1-d540-46a2-be50-eaa01bb23483)

**Output:**

**RTL**

**Timing Diagram**
![Screenshot 2024-11-12 180247](https://github.com/user-attachments/assets/34659374-11cc-4431-ae21-a7310dd4f956)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

