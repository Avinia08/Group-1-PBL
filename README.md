# Systolic-Array-Matrix-Multiplication
Implementation of stationary systolic array which has a size of 4x4

The MMU (Matrix Multiplication Unit) module is the top-level module that represents a systolic array for
matrix multiplication. It takes several inputs, processes them systolically through multiple MAC (Multiply-Accumulate)
units arranged in a 2D array, and produces an output accumulator result.
The MAC (Multiply-Accumulate) module represents a single multiply-accumulate unit. It takes inputs,
multiplies data with weight, accumulates the results, and produces output data and accumulation. Overall,
the MMU module orchestrates the interaction between multiple MAC modules, arranging them in a
systolic array fashion to perform matrix multiplication.The MAC module represents a single multiply-accumulate operation, with control for weight loading and accumulator reset. The design as a whole is intended for matrix multiplication operations in a systolic array configuration. Careful data and weight flow management ensures system correctness, confirmed through rigorous testing and verification procedures.
