# JavaScript Function Bug: Unexpected Behavior with Undefined Parameters

This repository demonstrates a common subtle bug in JavaScript functions related to the handling of undefined parameters.  The `foo` function is designed to add two numbers, but it doesn't handle the case where one of the input variables is undefined, resulting in unexpected behavior. The solution addresses this by explicitly checking for `undefined` values in addition to `null`.

## Bug

The original `bug.js` file contains a function that incorrectly handles undefined parameters, leading to unexpected results when one or both of the inputs are undefined.

## Solution

The `bugSolution.js` file provides a corrected version of the function, which gracefully handles both `null` and `undefined` parameters, returning 0 in those cases. This ensures the function behaves as intended regardless of the input values.  The improved logic explicitly checks for both `null` and `undefined` before performing the addition operation.