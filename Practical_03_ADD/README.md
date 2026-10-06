# Practical 3: ADD Operation on Two User-Entered Numbers

## Aim

To write and execute an assembly language program to read two user-entered numbers, add them, and display the sum using Mano's Basic Computer in CPU Sim.

## Theory

The `INP` instruction takes an integer input from the user and stores it in the AC register.

The first number is stored in memory using `STA A` because the second `INP` instruction overwrites the value in AC.

The `ADD A` instruction adds the value stored at memory location A to the value currently in AC.

Finally, `OUT` displays the result and `HLT` stops the program.

## Assembly Program

```asm
INP
STA A
INP
ADD A
STA SUM
OUT
HLT
A: .data 1 0
SUM: .data 1 0
