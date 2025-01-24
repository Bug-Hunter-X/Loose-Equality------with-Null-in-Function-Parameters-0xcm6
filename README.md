# Loose Equality (==) with Null in Function Parameters

This code demonstrates a potential issue when using loose equality (==) with null values in JavaScript function parameters.

## Bug Description
The function `foo` uses loose equality (`==`) to check if parameters `a` and `b` are null.  While this appears to work, it can lead to unexpected behavior because of JavaScript's loose equality type coercion.

## Reproduction

1. Run the `bug.js` file.
2. Observe the unexpected behavior where the function might not handle null values as intended.

## Solution
The recommended solution is to use strict equality (`===`) for better type safety and clarity.

## Solution Code
The `bugSolution.js` file shows the corrected version using strict equality.
