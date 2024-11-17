# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC

###  NAME: YOGESH RAO S D
### REGISTER NUMBER:212222110055
### DEPARTMENT: BE CSE(IOT)
### YEAR: III

## Aim:
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.</BR>
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.</BR>
Computer System: For programming and simulating the PLC ladder logic.</BR>
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.</BR>
Output Devices: LEDs or other indicators to visualize the results of operations.</BR>
Wires and Connectors: For interfacing input/output devices with the PLC.</BR>
Power Supply: Appropriate power supply for the PLC and peripherals.</BR>

## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:

### Arithmetic Operations:

#### Addition (ADD): 
Adds two values and stores the result in a specified memory location.</BR>

#### Subtraction (SUB): 
Subtracts one value from another.</BR>

#### Multiplication (MUL): 
Multiplies two values.</BR>

#### Division (DIV): 
Divides one value by another.</BR>

### Logical Operations:

#### AND Operation: 
The output is TRUE only when all inputs are TRUE.</BR>

#### OR Operation:
The output is TRUE when any input is TRUE.</BR>

#### NOT Operation: 
Inverts the input logic.</BR>

## Procedure:

Setup the PLC Programming Environment:</BR>
Connect the PLC to the computer and launch the PLC programming software.</BR>
Ensure all input and output devices are connected to the PLC’s I/O modules.</BR>

### Create Ladder Logic for Arithmetic Operations:</BR>

#### Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.</BR>
Set the operands (e.g., two values) and the destination to store the result.</BR>

#### Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.</BR>
Set the values and the destination to store the result.</BR>

#### Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.</BR>
Set the values and the destination to store the result.</BR>

#### Division (DIV):
Create a rung with an input linked to a DIV instruction.</BR>
Set the values and the destination to store the result.</BR>

### Create Ladder Logic for Logical Operations:

#### AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.</BR>
Assign an output to visualize when both inputs are TRUE.</BR>

#### OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.</BR>
Assign an output to visualize when any input is TRUE.</BR>

#### NOT Operation:
Create a rung with a single input connected to a NOT function.</BR>
Assign an output to visualize the inverted logic.</BR>

### Simulate the Ladder Logic:

#### Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.

#### Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.

## Outputs:
Arithmetic Operations: Verify that the output shows correct results for addition, subtraction, multiplication, and division.
Logical Operations: Confirm that the output behaves as expected based on the logical conditions (AND, OR, NOT).

##  Simulation Screenshots:

### Arithmetic Operations :

#### ADDITION :
![{18826A8C-91FA-4AF8-845E-4153D916203A}](https://github.com/user-attachments/assets/da35fb80-2f40-49d0-9031-c22d96bae41e)

#### SUBTRACTION :
![{86F06901-91F7-4997-81ED-53C8B6EC2EAF}](https://github.com/user-attachments/assets/89d76c35-45f3-4671-8bc8-e5bd281dadaf)

#### MULTIPLICATION :
![{91955638-030F-4772-BD7C-91EF960E485B}](https://github.com/user-attachments/assets/ef05d5f1-ed02-43f3-b70a-bb62a24dcdea)

#### DIVISION :
![{793AC6AF-5D72-4FC9-8D51-9703F822611E}](https://github.com/user-attachments/assets/6c2c0508-7bed-411a-ab39-c992d9f42655)

### Logical Operations :

#### AND :
![{3B1C1BAE-9413-440A-B19F-BE55F54B356C}](https://github.com/user-attachments/assets/d843a216-72fc-4ab9-a6fb-d535785c5128)

#### OR :
![{54846D83-7202-4770-9924-7048EBE48F90}](https://github.com/user-attachments/assets/65c527a3-5c13-4dec-bde5-7d43be7c1ae3)

#### NOT :
![{8D182062-6D11-47C0-A716-5ED1E5F9E25C}](https://github.com/user-attachments/assets/297d3684-3f5c-4e4e-83d5-430e1bd13e2d)

## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
