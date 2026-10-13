# Practical 10: Sum of Integers Until a Negative Number Is Read

## Aim
To write an assembly program that reads integers and adds them until a negative non-zero number is read, then outputs the sum without including the last negative number.

## Software Required
CPU Sim 4.0.11 and the BasicComputer.cpu machine.

## Theory
This program uses a sentinel-controlled loop. It keeps reading and adding non-negative integers. When a negative number is entered, the program stops adding and displays the total.

## Program File
`P10_SUM_UNTIL_NEGATIVE.a`

## Procedure
1. Open `BasicComputer.cpu` and `P10_SUM_UNTIL_NEGATIVE.a` in CPU Sim.
2. Set the RAM Data selector to Hex.
3. Press **Ctrl + 2** to assemble and load the program.
4. Press **Ctrl + R** to run the program.
5. Enter `4`, `10`, `0`, `6`, and `-3`, pressing Enter after each number.
6. Observe the output displayed in the console.

## Sample Input
4, 10, 0, 6, -3

## Expected Output
20

## Result
The program successfully adds the entered integers until a negative number is read and displays the sum, excluding the negative number.
