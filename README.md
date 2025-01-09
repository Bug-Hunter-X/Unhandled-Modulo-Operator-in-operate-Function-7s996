# Unhandled Modulo Operator in JavaScript Calculator

This repository demonstrates a common error in JavaScript: failing to handle all possible cases in a switch statement or conditional logic.  The `operate` function, intended to perform basic arithmetic, lacks support for the modulo operator (`%`).

## Bug Report

The `operate` function correctly handles addition, subtraction, multiplication, and division. However, attempting to use the modulo operator results in an 'Invalid operator' error.

## Solution

The solution involves adding a case for the modulo operator in the switch statement within the `operate` function.  This ensures that all expected operators are correctly handled.
