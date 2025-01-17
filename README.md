# Stack Overflow in Recursive Factorial Function

This repository demonstrates a common error in recursive functions: stack overflow. The `foo` function calculates the factorial of a number recursively.  For large inputs, this leads to a stack overflow because the recursive calls exceed the available stack space.  The solution demonstrates how to address this using iteration.

## How to reproduce

1.  Clone this repository.
2.  Run the `bug.hack` file using a Hack compiler/interpreter.
3. Observe the stack overflow error for sufficiently large inputs (e.g., foo(1000))

## Solution

The `bugSolution.hack` file provides an iterative solution that avoids the stack overflow issue.