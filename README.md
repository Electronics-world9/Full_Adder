# Full_Adder

Verilog Code for full adder
<br> Author- Priti
module full_adder(input A,B,Cin,output Sum,Cout);
assign Sum=A^B^Cin;
assign Cout=(A&B)|(B&C)|(A&C);
endmodule
