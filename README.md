# TypeScript Type Error: Passing Array to String Function

This repository demonstrates a common type error in TypeScript: passing an array to a function that expects a string.  The `greeter` function is defined to accept a string, but the `user` variable is an array of strings.  Attempting to pass `user` to `greeter` results in a type error.

The solution shows how to correctly handle this situation, either by modifying the function to accept an array or by selecting a single element from the array before passing it to the function.