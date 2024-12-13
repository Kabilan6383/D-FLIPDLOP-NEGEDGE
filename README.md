# D-FLIPDLOP-NEGEDGE

**AIM:**

To implement  D flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**D Flip-Flop**

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.

![Screenshot 2024-12-13 231958](https://github.com/user-attachments/assets/42c869f0-0438-4a5f-85b2-966bbb9f50a6)


This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.

![Screenshot 2024-12-13 232007](https://github.com/user-attachments/assets/1b6e7bfe-978b-46d7-8509-f35a80cacfd9)

Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D

![Screenshot 2024-12-13 232013](https://github.com/user-attachments/assets/881d9974-6092-4857-96da-c5e9799c1fcf)


Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.

**Procedure**

/* write all the steps invloved */

**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by:KABILAN P RegisterNumber:24900859
*/

**RTL LOGIC FOR FLIPFLOPS**
![Screenshot 2024-12-13 232023](https://github.com/user-attachments/assets/afa2e90a-1533-4ae5-9c15-59f46749e9f8)


**TIMING DIGRAMS FOR FLIP FLOPS**
![Screenshot 2024-12-13 232042](https://github.com/user-attachments/assets/3416e7db-910d-4617-b071-68e1b15ec044)


**RESULTS**
