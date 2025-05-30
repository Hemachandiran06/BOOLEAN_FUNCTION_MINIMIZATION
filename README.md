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


BOOLEAN MINIMIZATION

![WhatsApp Image 2024-12-21 at 08 56 17_19e0b7a3](https://github.com/user-attachments/assets/c11bef76-3e0e-494b-86ce-55b52fcbd903)
![WhatsApp Image 2024-12-21 at 08 56 30_6e070fb5](https://github.com/user-attachments/assets/358ba9f0-4d9f-4020-bc1a-5dccc6493ad4)

**TRUTH TABLE:**

i)F1
![image](https://github.com/user-attachments/assets/34c74a5d-4e82-4741-a6e2-bf0de1ade9a8)


ii)F2
![image](https://github.com/user-attachments/assets/79008ed0-2390-4424-b204-95f2bd1bee16)



**Program:**

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
 ```
module form(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
```
```
module Form2(x,y,z,w,f2);
input x,y,z,w;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```



Developed by:HEMACHANDIRAN J

RegisterNumber:24900182


**RTL**

F1
![Screenshot 2024-11-04 093124](https://github.com/user-attachments/assets/04c9dc43-35e4-4d7a-96c0-79892c9788a5)
F2
![image](https://github.com/user-attachments/assets/817fbe6a-d1ef-4349-ac18-2dc7e46c51ef)


**Output:**

F1
![Screenshot 2024-11-04 094418](https://github.com/user-attachments/assets/60521c61-cbc2-4305-b622-fd88f3a31842)
F2
![image](https://github.com/user-attachments/assets/46453dff-f950-436d-9db4-97ae83367440)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
