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
module exp2a(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d) | (a & b & ~c) | (~a & b & d));
endmodule
```
```
module exp2b(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2= ((~y&z)|(w&y)|(x&y));
endmodule
```


```
Developed by: HARISH.S
RegisterNumber: 2122242400052
```
**TRUTH TABLE**
F1

![image](https://github.com/user-attachments/assets/cf7ba25d-388a-4c9a-b48e-94f3e9abd293)
F2

![image](https://github.com/user-attachments/assets/6a7298fc-2584-4208-98e5-8c488f223224)

**RTL realization**
F1

![image](https://github.com/user-attachments/assets/aec4eab4-0f1d-4339-9482-143851a038af)
F2

![image](https://github.com/user-attachments/assets/9e23917c-6d57-4879-8e09-f2b410f30645)

**Output:**
F1

![image](https://github.com/user-attachments/assets/0af44406-f93e-4535-976a-66874359cbfd)
F2

![image](https://github.com/user-attachments/assets/049ade0f-e6eb-475b-b0f8-8621cd1b67dd)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

