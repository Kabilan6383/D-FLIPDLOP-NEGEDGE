# D-FLIPDLOP-NEGEDGE

**AIM:**

To implement  D flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**D Flip-Flop**

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.

![Screenshot 2024-12-13 231958](https://github.com/user-attachments/assets/7b19ed61-011d-423d-b383-979744d9b59f)


This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.

![Screenshot 2024-12-13 232007](https://github.com/user-attachments/assets/59f075d6-eee0-4734-8e9e-d5e641a02702)


Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D

![Screenshot 2024-12-13 232013](https://github.com/user-attachments/assets/4f374500-6720-4dc9-a97e-620ba80bcf14)


Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.

**Procedure**

 write all the steps invloved 

**PROGRAM**

 Program for flipflops and verify its truth table in quartus using Verilog programming. 
 
 Developed by:KABILAN P
 
 RegisterNumber:24900859

 module Dflop(d, clk, rst, q);
  
  input d, clk, rst;
  
  output reg q;
  

  always @(negedge clk or posedge rst) begin
    
  if (rst)
     
  q <= 0; // Reset the flip-flop
        
  else
      
  q <= d; // D input is passed to Q on the negative clock edge
 
  end

endmodule




**RTL LOGIC FOR FLIPFLOPS**

![Screenshot 2024-12-13 232023](https://github.com/user-attachments/assets/72948eff-710e-44a4-81d4-253402229c54)



**TIMING DIGRAMS FOR FLIP FLOPS**

![Screenshot 2024-12-13 232042](https://github.com/user-attachments/assets/3a49fff0-87d6-451f-895d-2ba86f40a51b)




**RESULTS**

The given Program for flipflops and verify its truth table in quartus using Verilog programming. 
