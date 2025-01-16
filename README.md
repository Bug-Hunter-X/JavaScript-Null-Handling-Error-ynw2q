# JavaScript Null Handling

This repository demonstrates a common error in JavaScript: not explicitly handling null or undefined values. The code provided shows how a function can be improved by adding a check for null values before performing arithmetic operations.

## Bug

The original code performs addition on parameters that might be null, leading to unexpected behavior.

## Solution

The solution adds a check for null values before performing the addition. This prevents errors and produces the expected results when null values are present.

## How to Run

1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` to see the original buggy code and the corrected version. 
3. Run the `.js` files in a JavaScript environment (e.g. Node.js).