
# Custom printf Implementation

## Overview

This project is part of the Holberton School curriculum and involves creating a custom implementation of the `printf` function in the C programming language. The standard `printf` is a powerful tool used to format and display output. By replicating its core functionalities, we aim to gain deeper insights into:

- **String formatting**: Handling and manipulating strings for output.
- **Variadic functions**: Functions that accept a variable number of arguments.
- **Low-level programming**: Writing efficient code with standard libraries and system calls.
- **Collaboration**: Working in a team to develop high-quality, functional software.

## Features

### Supported Format Specifiers:
- **`%c`**: Prints a single character.
- **`%s`**: Prints a string. If the string is `NULL`, it prints `"(null)"`.
- **`%d` / `%i`**: Prints an integer, including negative values, using a recursive helper function.
- **`%%`**: Prints the `%` character itself.

### Custom Functions:
#### `_printf`
**Prototype**:
```c
int _printf(const char *format, ...);


## Authors

- [@Naellito](https://www.github.com/Naellito)
- [@ginftls](https://www.github.com/ginftls)


![Logo](https://i.imgur.com/DUuV716.png)


