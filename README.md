# JavaScript Type Coercion Bug

This repository demonstrates a common JavaScript bug related to type coercion. The `foo` function is intended to add two numbers, but due to JavaScript's loose typing, it performs string concatenation when one of the inputs is a string.  The solution showcases how to explicitly enforce type checking to prevent this issue. 

## Bug

The `bug.js` file contains the buggy code. The function `foo` adds a number and a string, resulting in unexpected string concatenation instead of numerical addition.

## Solution

The `bugSolution.js` file provides a solution by adding type checking using `typeof` to ensure that both inputs are numbers before performing the addition.  This prevents type coercion and produces the expected numerical result.