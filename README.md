# JavaScript Loose Equality Bug with Null and Zero

This repository demonstrates a common JavaScript bug related to loose equality (==) when comparing null and 0.  Loose equality does not check the type of the operands while comparing and hence leads to unexpected behavior.

## Problem
The loose equality operator (==) in JavaScript can lead to unexpected results when comparing null and 0.  Null is loosely equal to 0, which can cause unexpected behavior if you're not careful.

## Solution
The recommended solution is to always use the strict equality operator (===) when comparing values in JavaScript. Strict equality checks both the value and the type of the operands and returns true only if both are same.  This prevents unexpected comparisons between null and 0.

## Usage
1. Clone this repository.
2. Open `bug.js` to see the buggy code.
3. Open `bugSolution.js` to see the corrected code using strict equality.
4. Run the JavaScript code using Node.js or your preferred JavaScript environment.