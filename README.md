# Julia Floating-Point Precision Bug

This repository demonstrates a common error in Julia related to floating-point number comparisons within conditional statements. The `myfunction` function is designed to square the input, but its behavior with floating-point numbers can be unpredictable due to how floating-point numbers are represented and compared.

The `bug.jl` file contains the buggy code, while `bugSolution.jl` shows a corrected version using a tolerance for comparison.