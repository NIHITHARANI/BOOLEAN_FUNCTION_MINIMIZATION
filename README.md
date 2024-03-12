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
```python
module flipflops(a,b,Y1,Y2,Y3,Y4,Y5,Y6,Y7);
input a,b;
output Y1,Y2,Y3,Y4,Y5,Y6,Y7;
and(Y1,a,b);
or(Y2,a,b);
not(Y3,a);
xor(Y4,a,b);
nand(Y5,a,b);
nor(Y6,a,b);
xnor(Y7,a,b);
endmodule
```
## Logic symbol & Truthtable

 ![image](https://github.com/23004513/study-of-basic-gates/assets/138973069/0637a1e9-8297-4190-9169-3b3ca939cf6b)

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:B.NIHITHA RANI
RegisterNumber:212223040131


**RTL realization Output:**
![image](https://github.com/23004513/study-of-basic-gates/assets/138973069/c8aa777f-970e-4d33-b3d1-c042ecca8581)

**RTL**
![image](https://github.com/23004513/study-of-basic-gates/assets/138973069/2d8a4e26-bb61-4984-bd36-a8edf62b9434)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

