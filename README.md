# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**![WhatsApp Image 2024-10-28 at 14 26 37_b6f80063](https://github.com/user-attachments/assets/4d00ec95-3b26-4c6d-a117-dbda423734c5)


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module exp2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 


Developed by: RegisterNumber:*/ 24900175


**RTL realization**
![Screenshot 2024-11-11 091145](https://github.com/user-attachments/assets/64bbae1d-a7e7-4c9d-88b7-dd0317778dfc)

**Output:**

**RTL**

**Timing![Screenshot 2024-11-11 091525](https://github.com/user-attachments/assets/90f34400-0b90-4ec5-8e28-3eba506a0735)
 Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

