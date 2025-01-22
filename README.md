# TCSS371
## Assignment 2: Digital Logic Structure
### Raiden H

## Problem 1
Build the following circuits in Logisim Evolution using only AND, OR, and NOT gates.

### a) 
A 10-to-1 mux. Label inputs and outputs. Provide a truth table for the circuit in the circuit diagram.

### b)
An 8-bit full adder. Create a 1-bit adder first and use it to build the full one. Label the inputs and outputs. 
A truth table is not required. You can use a constant `0` as the carry for the least significant bit

### c)
An 8-bit D-Latch. Create a 1-bit gated D-Latch first, then use it as a building block. Label the inputs and outputs. 
A truth table is not required.

## Problem 2
Create a truth table for a 4-bit input where the output will be `1` if the decimal number represented by the bit input 
is divisable by 3 and/or 5. Assume that `ABCD` represents the most-to-least significant bits of the input.

Use the implementation pattern discussed in lecture.

## Problem 3
Design a 4-bit ALU with 3 select lines {NOTA, NOTB, AND, NAND, OR, NOR, XOR, ADD}. Inputs are 2 4-bit numbers and a carry in bit. Outputs are a 4-bit number and a carry out bit.

Carry-out should always be `0` if the ADD operation is not chosen and there is no carry. Carry-out should never be `ERROR`.
