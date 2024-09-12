# 0x11. C - printf

## Project Description

This project is a custom implementation of the `printf` function in C. The goal is to recreate the functionality of the standard `printf` function from the `<stdio.h>` library. This custom `_printf` function will handle various format specifiers and produce output according to a format string.

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- Allowed languages: `C`
- A README.md file, at the root of the folder of the project is mandatory
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- You are not allowed to use global variables
- No more than 5 functions per file
- The prototypes of all your functions should be included in your header file called main.h
- All your header files should be include guarded
- You are not allowed to use any library that handles printing for you (like `printf`, `puts`, etc.)
- `main` functions are provided separately

## Authorized functions and macros

    - `write (man 2 write)`
    - `malloc (man 3 malloc)`
    - `free (man 3 free)`
    - `va_start (man 3 va_start)`
    - `va_end (man 3 va_end)`
    - `va_copy (man 3 va_copy)`
    - `va_arg (man 3 va_arg)`

## Compilation

`gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c`

## Disclaimer

The code is written in C and is a custom implementation of the `printf` function. It is not a direct copy of the standard `printf` function from the `<stdio.h>` library and so it contains some limitations and bugs.
