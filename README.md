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
Developed by: S.Navadeep
RegisterNumber: 212224230180
```

**TRUTH TABLE**

F1

![image](https://github.com/user-attachments/assets/140fbfac-669c-4267-ac01-a6353bfa4aa7)

F2

![image](https://github.com/user-attachments/assets/3cf32c39-2d4a-4241-91da-3a62ad47c658)


**RTL realization**

F1

![image](https://github.com/user-attachments/assets/61e1186c-103d-4b45-9ae0-28d65242a713)

F2

![image](https://github.com/user-attachments/assets/e31de6ac-6a06-4206-b2c9-ac8fde7a2ac4)


**Output:**

F1

![image](https://github.com/user-attachments/assets/acb71e64-8daa-4ef5-8391-c5770d9f6054)

F2

![image](https://github.com/user-attachments/assets/d85abf7a-3737-45a6-9c86-fe58d35f0739)




**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

