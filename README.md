# JavaScript Bug: Incorrect Handling of Undefined Values

This repository demonstrates a common JavaScript error involving the improper handling of undefined values in a function. The function `foo` is intended to add two numbers, but it only explicitly checks for `null` values. If either input is `undefined`, it throws a `TypeError`. 

The solution demonstrates how to properly handle both `null` and `undefined` values, preventing the error and making the function more robust.

## Bug

The `bug.js` file contains the buggy function that only handles `null` input but fails for `undefined` input, leading to type errors.

## Solution

The `bugSolution.js` file shows the corrected function, where `undefined` values are properly handled using loose equality checking.