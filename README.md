# Unexpected Type Coercion in JavaScript

This repository demonstrates a common, yet subtle, error in JavaScript: unexpected type coercion with the + operator.  When using the + operator with a mix of numbers and strings, JavaScript will perform string concatenation instead of numerical addition. This can lead to unexpected results if not handled carefully. 

The `bug.js` file shows the issue, and `bugSolution.js` provides a solution.

## How to Reproduce
1. Clone this repository.
2. Open `bug.js` in your preferred JavaScript environment.
3. Run the code and observe the unexpected output.

## Solution
The `bugSolution.js` file demonstrates how to avoid this issue by explicitly converting strings to numbers using `parseInt()` or `Number()` before performing arithmetic operations.