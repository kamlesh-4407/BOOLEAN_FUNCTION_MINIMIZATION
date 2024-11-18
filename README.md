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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

```

Developed by:Kamlesh.y RegisterNumber:24003690


**RTL realization**

**Output:**

**RTL**
![image](https://github.com/user-attachments/assets/bfa5a742-e275-4b04-bc1a-5f950c13a926)



**Timing Diagram**
![image](https://github.com/user-attachments/assets/c57db7ac-3eee-4a1b-adde-ff6ad2a42d14)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

