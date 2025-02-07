# Python RecursionError Example

This repository demonstrates a common error in recursive functions in Python: the `RecursionError` caused by exceeding the maximum recursion depth.

The file `bug.py` contains a factorial function that does not handle negative input correctly. This results in infinite recursion and a `RecursionError`. The solution in `bugSolution.py` adds a check for negative input, preventing the error.

## How to reproduce the error
1. Clone this repository.
2. Run `bug.py` using a Python interpreter.
3. Observe the `RecursionError`. 

## How to fix the error
1. Examine the `bugSolution.py` file.
2. Note how the `if` condition handles negative input values. 

This example highlights the importance of carefully considering all possible inputs when writing recursive functions.