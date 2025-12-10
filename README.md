AIM

To implement Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED: Quartus prime

THEORY

Encoder 8 To 3

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

image


![WhatsApp Image 2025-12-10 at 20 29 21_f9d0458a](https://github.com/user-attachments/assets/a7e57a82-4906-4126-99cd-0561fe6b942d)


Truth Table


![WhatsApp Image 2025-12-10 at 20 29 35_f314403a](https://github.com/user-attachments/assets/ea79ee28-196e-45f3-8f80-624a6a03cd91)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

image
![WhatsApp Image 2025-12-10 at 20 29 47_1f73226b](https://github.com/user-attachments/assets/a0e5827b-3c3b-4797-997f-f761f4c8657b)

Procedure

* Create project in Quartus.

* Write Verilog code for encoder.

* Add file to project.

* Compile the design.

* Simulate and check outputs.

PROGRAM


 Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming.

Developed by:GOKULAVANI.R

RegisterNumber:25017080

RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling

TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling

RESULT


thus we implement encoder 8 to 3 in dataflow modelling using verilog and validating their functionality using functionality table has been done using Quartus software.
