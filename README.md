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

![WhatsApp Image 2024-12-09 at 21 53 16_b7eee390](https://github.com/user-attachments/assets/52f8c23d-4421-4d52-b337-292a4ff6823f)

The logical expression of the term a, b, and c are as follows:

a = y1 + y3 + y5 + y7

b = y2 + y3 + y6 + y7

c = y4 + y5 + y6 + y7

Logical circuit of the above expressions is given below:

![WhatsApp Image 2024-12-09 at 21 56 40_c01b5e11](https://github.com/user-attachments/assets/9b61d313-1b3d-4707-99cb-65134b6ba69b)

Figure 02  Encoder 8 * 3

**Procedure**

/* write all the steps invloved */

**PROGRAM**

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by: Dinesh.V 

RegisterNumber: 24010667

module encoder(a,b,c,y0,y1,y2,y3,y4,y5,y6,y7);

input y0,y1,y2,y3,y4,y5,y6,y7;

output a,b,c;

assign a= ( y4 | y5 | y6 | y7);

assign b= ( y2 | y3 | y6 | y7);

assign c= ( y1 | y3 | y5 | y7);

endmodule


**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**

![WhatsApp Image 2024-12-09 at 21 56 40_2e235c91](https://github.com/user-attachments/assets/5f4b3258-3871-4b71-a734-43f1e550528a)


**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**

**RESULTS**

Thus the truth table of Encoder 8 to 3 in Dataflow Modelling in Quartus || using verilog programming are studied, verified and executed successfully.



