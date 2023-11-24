# Name
Amaljosh Maadhav J
# Roll No
23014023
# Experiment 02
Implementation of combinational logic gates
# Aim
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
# Equipments Required
Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime
# Theory
# Procedure
# Program
module deex2(A,B,C,D,F1);

input A,B,C,D;

output F1;

wire x1,x2,x3,x4,x5;

assign x1=(~A)&(~B)&(~C)&(~D);

assign x2=(A)&(~C)&(~D);

assign x3=(~B)&(C)&(~D);

assign x4=(~A)&(B)&(C)&(D);

assign x5=(B)&(~C)&(D);

assign F1=x1|x2|x3|x4|x5;

endmodule
# RTL realisation
![Exp 02 RTL realisation](https://github.com/amal-2006/Experiment--02-Implementation-of-combinational-logic-/assets/148410730/bce0eba8-f13d-4d55-8627-74b6c130b0d5)

# Truth Table
![Exp 02 Truth Table](https://github.com/amal-2006/Experiment--02-Implementation-of-combinational-logic-/assets/148410730/85e547b6-1c5e-4c80-8ed1-f281fa2b589b)

# Timing Diagram
![Exp 02 Timing Diagram](https://github.com/amal-2006/Experiment--02-Implementation-of-combinational-logic-/assets/148410730/6fb71a8b-96a8-4403-abf9-0adc920492af)

# Result
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.








 

 
 
 




 


