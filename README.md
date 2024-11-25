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

    module deexp2(a,b,c,d,w,x,y,z,f1,f2);
    input a,b,c,d,w,x,y,z;
    output f1,f2;
    assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
    assign f2=((~y & z)|( w & y )|(x & y));
    endmodule


#Developed by:A Praneya

#RegisterNumber: 24900343



**RTL realization**

**Output:**

![exp2ss](https://github.com/user-attachments/assets/56bac347-61b5-4a83-aa10-d1ee7b3260d8)


**RTL**

**Timing Diagram**

![exp2wss](https://github.com/user-attachments/assets/13c168c7-038c-4bf5-bd7f-6132b50fd9c2)


**Result:**

Thus the given logic functions are implemented  and their operations are verified using Verilog programming.

