# JavaScript Function: Unexpected Behavior with Undefined Arguments

This repository demonstrates a common JavaScript error related to how functions handle undefined arguments.  The `foo` function correctly handles `null` inputs, but it fails when passed `undefined` arguments.

## Bug

The original `foo` function lacks explicit handling for `undefined` values.

## Solution

The improved `foo` function uses loose comparison (`==`) to check for both `null` and `undefined` values.

## How to Run

1. Clone this repository.
2. Open `bug.js` to see the buggy code and `bugSolution.js` for the solution.
3. Run the files using a JavaScript runtime (e.g., Node.js).
