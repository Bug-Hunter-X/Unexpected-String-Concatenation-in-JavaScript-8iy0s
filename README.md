# Unexpected String Concatenation in JavaScript

This example demonstrates a common JavaScript issue: the implicit type coercion that leads to string concatenation when adding numbers and strings.  The function `foo` intends to add two numbers, but because one input is a string, JavaScript interprets the '+' operator as string concatenation, producing the unexpected result '12' instead of 3.

The solution emphasizes explicit type checking and conversion to ensure the addition operation behaves as intended.