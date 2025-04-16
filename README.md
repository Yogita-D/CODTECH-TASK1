# CODTECH-TASK1
Name - Yogita Shrikant Dhonge
Company - CODETECH IT SOLUTIONS
ID - CT04WM47
Domain -VLSI
Duration -March 18th,2025 to April 18th,2025
Mentor - Vaishali

Here's an overview of the alu_32bit_case Verilog module:


---

Module Name: alu_32bit_case

Purpose:

This module implements a 32-bit Arithmetic Logic Unit (ALU) using a case statement, performing different operations based on a 3-bit control input f.


---

Inputs:

a [31:0]: First 32-bit input operand

b [31:0]: Second 32-bit input operand

f [2:0]: 3-bit function selector (control signal)


Output:

y [31:0]: 32-bit result of the selected ALU operation



---

Functionality:

Based on the value of f, the module performs the following:


---

Use Case:

This ALU is typically used in processors or digital systems that require a small set of arithmetic and logic operations. The control signal (f) determines which operation the ALU will execute on the given operands.
