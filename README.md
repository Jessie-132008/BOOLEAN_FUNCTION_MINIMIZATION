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
 i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
 ```

Developed by: RegisterNumber:25017372 Name:JESSIE J


**RTL realization**
  <img width="1920" height="1080" alt="experiment2result" src="https://github.com/user-attachments/assets/6ed81bd3-7365-4b4a-937e-315ade953692" />
  <img width="1920" height="1080" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/bcc2e6dc-7ad5-499f-89e8-1f6e23a77a2f" />
**Output:**
 <img width="1920" height="1080" alt="experiment 2 1" src="https://github.com/user-attachments/assets/80198bed-1749-4aca-b093-d91a0d52bb7c" />
 <img width="1920" height="1080" alt="experiment2 2" src="https://github.com/user-attachments/assets/2413f136-2aec-4dff-971d-01efafddb2af" />

**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

