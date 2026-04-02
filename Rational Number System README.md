# Rational Number System

## Overview

This project file implements a `Rational` class in C++ for representing and manipulating rational numbers (fractions) with automatic normalization.

## Features
 
- Numerator and denominator storage
- Denominator validation to prevent zero values
- Automatic sign correction so denominator stays positive
- Reduction to lowest terms using the greatest common divisor (GCD)
- Constructors for default values, integer values, and copy construction
- Conversion to decimal using `toDecimal()`
- Reciprocal generation using `reciprocal()`
- Display as `numerator/denominator`
- Arithmetic operators: `+`, `-`, `*`, `/`
- Compound assignment operators: `+=`, `-=`, `*=`, `/=`
- Comparison operators: `==`, `!=`

## Usage

1. Include the file in a C++ project or use the `Rational` class directly.
2. Construct rational numbers with `Rational(num, den)` or `Rational(num)`.
3. Use arithmetic and comparison operators naturally in expressions.
4. Call `display()` to print the rational number or `toDecimal()` for a floating point representation.

## Notes

- Division by a rational number with numerator zero is explicitly handled with an error message and program termination.
- The source file is currently commented out, so uncomment the code before compiling.
