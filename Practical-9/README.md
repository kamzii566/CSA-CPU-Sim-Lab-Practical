# Practical 9: Register-reference Instructions — CIR, CIL

## Aim
To simulate the CIR and CIL instructions and determine the values of AC, E, PC, AR and IR in decimal after execution.

## Software Required
CPU Sim 4.0.11 and the BasicComputer.cpu machine.

## Theory
- **CIR (Circulate Right):** Rotates the combined contents of the E register and AC one bit to the right.
- **CIL (Circulate Left):** Rotates the combined contents of the E register and AC one bit to the left.

These instructions rotate the bits without losing any bit.

## Program File
`P09_REGISTER_REF_CIR_CIL.a`

## Procedure
1. Open `BasicComputer.cpu` in CPU Sim.
2. Open `P09_REGISTER_REF_CIR_CIL.a`.
3. Press **Ctrl + 2** to assemble and load the program.
4. Press **Ctrl + D** to enter debug mode.
5. Set the Registers Data selector to **Unsigned Dec** and the RAM Data selector to **Hex**.
6. Click **Step by Instr** six times, recording AC, E, PC, AR and IR after each instruction.
7. Observe the final register values after HLT executes.

## Result
The CIR and CIL instructions are simulated successfully. After execution, the final register values are:

- AC = 9
- E = 0
- PC = 6
- AR = 1
- IR = 28673
