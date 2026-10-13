# Practical 11: Sum of Integers Until Zero Is Read

## Aim
To write an assembly program that reads integers and adds them until zero is read, then outputs the sum.

## Software Required
CPU Sim 4.0.11 and the BasicComputer.cpu machine.

## Theory
The program uses zero as a sentinel value. It reads and adds integers, including negative numbers, until zero is entered. The zero is not added to the sum.

## Program File
`P11_SUM_UNTIL_ZERO.a`

## Procedure
1. Open `BasicComputer.cpu` and `P11_SUM_UNTIL_ZERO.a` in CPU Sim.
2. Set the RAM Data selector to Hex.
3. Press **Ctrl + 2** to assemble and load the program.
4. Press **Ctrl + R** to run the program.
5. Enter `8`, `12`, `-5`, and `0`, pressing Enter after each number.
6. Observe the output in the console.

## Sample Input
8, 12, -5, 0

## Expected Output
15

## Result
The program successfully adds integers until zero is read and displays the sum, excluding the zero sentinel.
