# BOOLEAN_FUNCTION_MINIMIZATION
## DEVELOPED BY: KEERTHANA D
## REG NO: 212224040155
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

 module funct1(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
 endmodule

module funct2(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y&z)|(w&y)|(x&y));
 endmodule


**RTL realization**

**Output:**

**RTL**
![Screenshot (35)](https://github.com/user-attachments/assets/c010beae-2847-4284-8c7a-b99ebbd6196f)
![Screenshot (37)](https://github.com/user-attachments/assets/024b7397-3d3a-4a16-94b5-6fa8195e11a8)


**Timing Diagram**
![Screenshot (36)](https://github.com/user-attachments/assets/bdc69d9f-8243-4c78-ab8f-5b56f33235ca)
![Screenshot (38)](https://github.com/user-attachments/assets/ab51c130-467b-4abf-9527-44ac3a4ac32f)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

