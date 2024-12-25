# printf Project

## Overview
This repository contains the implementation of a custom `printf` function built as part of the 1337 (42 Network) curriculum. The goal of this project was to recreate the behavior of the standard C library function `printf` to gain a deeper understanding of variadic functions, formatted output, and low-level programming techniques.

## Features
Our custom `printf` function supports the following:

- **Format specifiers**:
  - `%c` : Prints a single character
  - `%s` : Prints a string of characters
  - `%d` or `%i` : Prints signed integers
  - `%u` : Prints unsigned integers
  - `%x` or `%X` : Prints hexadecimal numbers (lowercase/uppercase)
  - `%p` : Prints a pointer address
  - `%%` : Prints a percent sign

- **Behavior**:
  - Handles width and precision modifiers for supported specifiers.
  - Handles edge cases such as `NULL` strings or very large numbers.

## Learning Objectives
Through this project, I:

- Mastered the use of variadic functions (`va_list`, `va_start`, `va_arg`, `va_end`).
- Improved my understanding of the inner workings of the standard C library.
- Gained proficiency in memory management and edge case handling.
- Strengthened debugging and testing skills to ensure correctness.
