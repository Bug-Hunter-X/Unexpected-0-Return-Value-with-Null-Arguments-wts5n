# Unexpected 0 Return Value with Null Arguments in JavaScript

This repository demonstrates a subtle bug in JavaScript function handling null arguments.  The `foo` function is designed to add two numbers. However, when either argument is null, it unexpectedly returns 0 instead of NaN, which could lead to incorrect calculations or masking of actual errors. The bug is fixed in bugSolution.js