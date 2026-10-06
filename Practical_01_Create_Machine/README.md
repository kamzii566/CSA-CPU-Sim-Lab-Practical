# Practical 1: Create a Machine Based on Basic Computer Architecture

## Aim
To create a machine based on Mano's Basic Computer architecture using CPU Sim.

## Registers
- AC – 16 bits
- DR – 16 bits
- AR – 12 bits
- PC – 12 bits
- IR – 16 bits
- E – 1 bit
- TMP – 1 bit
- S – 1 bit

## Memory
- RAM name: M
- Length: 4096
- Cell size: 16 bits

## Microinstructions
The required microinstructions were created for:
- Data transfer
- Memory access
- Increment
- Arithmetic
- Logical operations
- Shift operations
- Set operations
- Test operations
- Decode
- I/O
- Halt

## Fetch Sequence
1. PC → AR
2. M[AR] → IR
3. PC + 1 → PC
4. IR(0-11) → AR
5. Decode IR

## Testing
The machine was tested using:

INP  
OUT  
HLT

Input: **25**

Output: **25**

## Result
The Basic Computer machine was successfully created and tested in CPU Sim.
