# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions

![image](https://github.com/user-attachments/assets/84c69e08-4da7-4021-9b0c-4500ecb71f18)

![image](https://github.com/user-attachments/assets/34c895f5-ebe0-462d-9bc4-aacdc7c7b0be)


**Truth Table**

![image](https://github.com/user-attachments/assets/e7bc94bf-838e-48f8-a319-47cc4d40307b)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```
Developed by:KAMLESH.Y RegisterNumber:24003690

**Output:**

**RTL**

Boolean function minimization f1
![image](https://github.com/user-attachments/assets/e985dbd7-7cb8-465d-a22e-9c8a62776f7b)

Boolean function minimization f2
![image](https://github.com/user-attachments/assets/944fd430-d319-47b3-a2ce-36ba9372a21d)


**Timing Diagram**

Boolean function minimization f1
![image](https://github.com/user-attachments/assets/e902c3e1-9b22-406d-a4ab-f1f8064d4b5a)

Boolean function minimization f2
![image](https://github.com/user-attachments/assets/e077bbe3-64d3-4ca4-a1df-30a7bef26c70)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

