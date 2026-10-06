# Practical 2: Fetch Routine

## Aim
To create and test the fetch routine of Mano's Basic Computer using CPU Sim.

## Fetch Sequence

The fetch sequence consists of the following microinstructions:

1. PC → AR
2. M[AR] → IR
3. PC + 1 → PC
4. IR(0-11) → AR
5. Decode IR

## Testing
The fetch sequence was tested using CPU Sim in Debug Mode.

Each microinstruction was executed step-by-step using **Step by Micro**.

## Result
The fetch routine was successfully created and tested in CPU Sim.
