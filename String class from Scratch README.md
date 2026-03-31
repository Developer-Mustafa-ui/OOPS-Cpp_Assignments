# String Class from Scratch

## Overview

This project file implements a custom `MyString` class in C++ for basic string management and manipulation without using the C++ `std::string` class.

## Features

- Manual storage of character arrays using dynamic memory
- Constructors for empty strings, C-string input, and copy construction
- Custom assignment operator
- Case conversion methods: `toUpperCase()`, `toLowerCase()`, `toSentenceCase()`
- Word counting with `countWords()`
- String reversal and concatenation
- Comparison operators: `==`, `!=`, `<`, `>`
- Index access via `operator[]`
- Function call operator `operator()()` to create a reversed copy
- Stream operators `<<` and `>>` for I/O
- Interactive menu-driven demonstration in `main()`

## Usage

1. Include the file in a C++ project.
2. Create `MyString` objects and use the provided methods to manipulate strings.
3. Use the interactive menu in `main()` to test the core string operations.

## Notes

- The source file is implemented using raw pointers, so correct memory management is essential.
- The code is currently commented out; uncomment the source before compiling.
- The interactive demo uses `system("pause")` for Windows console behavior.
