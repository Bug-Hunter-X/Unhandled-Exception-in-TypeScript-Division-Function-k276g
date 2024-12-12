# Unhandled Exception in TypeScript

This repository demonstrates a common error in TypeScript: unhandled exceptions. Specifically, the `divide` function can throw an error if the divisor is zero.

## Bug

The `bug.ts` file contains a function that performs division. If the denominator is zero, the function throws an error, causing the program to halt unexpectedly.  This isn't user-friendly. 

## Solution

The `bugSolution.ts` demonstrates how to handle the exception using a `try...catch` block, providing a more robust and user-friendly experience.

## How to Run

1. Clone this repository.
2. Compile and run the TypeScript files using a TypeScript compiler (tsc) and Node.js.

This example highlights the importance of exception handling for creating more reliable applications.