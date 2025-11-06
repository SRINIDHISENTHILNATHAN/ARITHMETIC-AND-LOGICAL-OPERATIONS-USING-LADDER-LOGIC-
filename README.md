# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME: SRINIDHI SENTHIL
# REGISTER NUMBER: 212222230148
# DEPARTMENT:BTECH AI&DS
# YEAR:VI
## Aim:
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.
Output Devices: LEDs or other indicators to visualize the results of operations.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.
## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:
Arithmetic Operations:

Addition (ADD): Adds two values and stores the result in a specified memory location.
Subtraction (SUB): Subtracts one value from another.
Multiplication (MUL): Multiplies two values.
Division (DIV): Divides one value by another.
Logical Operations:

AND Operation: The output is TRUE only when all inputs are TRUE.
OR Operation: The output is TRUE when any input is TRUE.
NOT Operation: Inverts the input logic.
Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Arithmetic Operations:

Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.
Set the operands (e.g., two values) and the destination to store the result.
Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.
Set the values and the destination to store the result.
Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.
Set the values and the destination to store the result.
Division (DIV):
Create a rung with an input linked to a DIV instruction.
Set the values and the destination to store the result.
Create Ladder Logic for Logical Operations:

AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.
Assign an output to visualize when both inputs are TRUE.
OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.
Assign an output to visualize when any input is TRUE.
NOT Operation:
Create a rung with a single input connected to a NOT function.
Assign an output to visualize the inverted logic.
Simulate the Ladder Logic:

Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.
Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.
Download and Execute:

Download the ladder logic program to the PLC if available and run it.
Test the arithmetic and logical operations with physical push buttons and observe the LEDs or other output devices.


## Outputs:
Arithmetic Operations: Verify that the output shows correct results for addition, subtraction, multiplication, and division.
Logical Operations: Confirm that the output behaves as expected based on the logical conditions (AND, OR, NOT).
##  Simulation Screenshots:
<img width="1055" height="464" alt="image" src="https://github.com/user-attachments/assets/8a05ffd5-1f23-49e5-9f91-d4dbae557315" />
<img width="1092" height="698" alt="image" src="https://github.com/user-attachments/assets/09b61560-3aca-457a-9e89-f226fbd3d321" />
<img width="1374" height="595" alt="image" src="https://github.com/user-attachments/assets/a52ba9ac-5e72-4496-999d-61dcd5d2adad" />
<img width="1191" height="188" alt="image" src="https://github.com/user-attachments/assets/13d9a999-e545-4417-9eaf-916565d5eec8" />

<img width="1285" height="387" alt="image" src="https://github.com/user-attachments/assets/4559751c-9f64-40fc-923b-d2339f964c21" />

###  ADDITION

<img width="1498" height="382" alt="image" src="https://github.com/user-attachments/assets/f6af3147-8653-4b2a-8f0a-3c949462213a" />

<img width="954" height="239" alt="image" src="https://github.com/user-attachments/assets/b1d366de-8ea9-4585-9c52-551bdb6617f7" />

###  SUBTRACTION

<img width="1288" height="384" alt="image" src="https://github.com/user-attachments/assets/25595b74-0b32-4ce5-950b-43d92e376597" />

<img width="796" height="236" alt="image" src="https://github.com/user-attachments/assets/bc4fcd95-056b-4468-bca3-f5142b96eb81" />

### MULTIPLICATION
<img width="1283" height="380" alt="image" src="https://github.com/user-attachments/assets/098f42c1-5bf4-416c-92a5-88919f9304cd" />

<img width="909" height="246" alt="image" src="https://github.com/user-attachments/assets/4203f1f0-22e0-4210-94df-775cf7c89e76" />

### DIVISION
<img width="1292" height="381" alt="image" src="https://github.com/user-attachments/assets/71cabda0-8f8b-4c91-a2c9-54c9cffa51a5" />

<img width="1027" height="245" alt="image" src="https://github.com/user-attachments/assets/d81ddfb7-f11c-43bb-8860-53ee913f6f99" />

### OR GATE

<img width="1287" height="386" alt="image" src="https://github.com/user-attachments/assets/8933f96b-f83e-40ea-b19b-162d1f73d467" />

<img width="796" height="240" alt="image" src="https://github.com/user-attachments/assets/48af4e85-aed9-48a8-a8c2-3c47c510380c" />


### WAND GATE
<img width="1290" height="393" alt="image" src="https://github.com/user-attachments/assets/f48573bd-4fcb-49cb-89c4-df428ee11870" />

<img width="839" height="250" alt="image" src="https://github.com/user-attachments/assets/40682bcc-c7db-48c2-8918-6c0d1f93130c" />

### WXOR GATE
<img width="1286" height="385" alt="image" src="https://github.com/user-attachments/assets/50b70f1a-68fa-4a5c-8d65-6e25b2539e3b" />

<img width="842" height="250" alt="image" src="https://github.com/user-attachments/assets/463e87ef-59d0-44a3-ae12-4930bd0698a5" />

### NEGATION
<img width="1287" height="382" alt="image" src="https://github.com/user-attachments/assets/73e62010-8017-449e-a706-103f2413bb7f" />

<img width="698" height="187" alt="image" src="https://github.com/user-attachments/assets/14d7a770-74fd-4754-825f-a3d9ec37ff04" />

### INCREASE
<img width="1286" height="388" alt="image" src="https://github.com/user-attachments/assets/f4b7dd59-55d4-4132-bed0-7c5ae0d2b704" />


<img width="696" height="190" alt="image" src="https://github.com/user-attachments/assets/96a533d7-fa9c-4c50-9cff-54edb7bd8e1a" />


### DECREASE

<img width="1292" height="391" alt="image" src="https://github.com/user-attachments/assets/ec5b17ff-7073-4e21-8f30-ede33a7a3a60" />

<img width="669" height="205" alt="image" src="https://github.com/user-attachments/assets/96261c99-d7f8-490a-b697-37dec02611aa" />


## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
