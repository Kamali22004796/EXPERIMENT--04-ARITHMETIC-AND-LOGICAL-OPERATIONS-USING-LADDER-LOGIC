# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME:KAMALI E
# REGISTER NUMBER:212222110015
# DEPARTMENT:CSE IOT
# YEAR:3RD 0
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

ADDITION:

![image](https://github.com/user-attachments/assets/decc225f-5154-4f2e-9f70-7aa927e298da)

SUBTRACTION :

![image](https://github.com/user-attachments/assets/1294d6e9-4d57-4bc3-9e00-506dfb79f645)

MULTIPLICATION :

![image](https://github.com/user-attachments/assets/9f609fbd-34e6-45d6-b452-5d3fdf5874db)

DIVISION :

![image](https://github.com/user-attachments/assets/f9387092-0577-4700-bb46-84d4a536bec5)

Logical Operations :
AND :

![image](https://github.com/user-attachments/assets/cc8f5038-cae1-4e16-a295-100d4643b0a7)

OR:

![image](https://github.com/user-attachments/assets/bef0426f-a15b-4917-a18f-dff270bfa26c)

NOT:

![image](https://github.com/user-attachments/assets/f61b0743-b013-45a7-ba4e-9f09a9ee5a93)


## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
