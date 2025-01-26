# Hack Recursion Stack Overflow

This repository demonstrates a common error in recursive functions written in Hack: stack overflow errors.  The `foo` function calculates the factorial of a number using recursion.  However, if the input is too large, the recursive calls consume excessive stack space, resulting in a stack overflow error. The solution demonstrates using iteration to avoid this problem.

## How to Reproduce

1. Clone this repository.
2. Compile and run `bug.hack`.  You will observe a stack overflow error with larger input.
3. Compile and run `bugSolution.hack`. This version uses iteration and will not overflow.