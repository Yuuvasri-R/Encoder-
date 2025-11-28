### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**

1.Create a Verilog module with 2 inputs and 4 outputs.

2.Write dataflow logic using assign statements to convert 8-bit input into 3-bit output.

3.Ensure only one input is HIGH at a time.

4.Compile and simulate the design.

5.Verify output using the truth table.

**PROGRAM**

<img width="623" height="168" alt="image" src="https://github.com/user-attachments/assets/6e0209b6-7d35-4308-99a1-6ac87f4f0d93" />


Developed by:Yuuvasri R
RegisterNumber:25003422


**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**
<img width="882" height="717" alt="image" src="https://github.com/user-attachments/assets/ab53e9c7-1cd1-4d1d-8b28-32e6590e6936" />


**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**
<img width="1913" height="596" alt="image" src="https://github.com/user-attachments/assets/6e69c503-d1a1-4ce6-8d41-4d945dfa8678" />

**RESULTS**

implementing Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables executed succesfully.


