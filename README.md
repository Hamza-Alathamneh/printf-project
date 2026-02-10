# printf Implementation in C

A simple `printf` implementation using C and the `<windows.h>` library. This project was created to practice and master the use of variadic functions (`va_arg`, `va_start`, `va_end`).

## Features

- Supports basic format specifiers:
  - `%c` - Print a single character
  - `%s` - Print a string
  - `%%` - Print a percent sign
- Handles invalid format specifiers gracefully
- Returns the number of characters printed (matching standard `printf` behavior)

## Usage Example

```c
#include "main.h"

int main(void)
{
    _printf("Hello %s!\n", "World");
    _printf("Character: %c\n", 'A');
    _printf("Percentage: %%\n");
    return (0);
}

this code will only work on windows since <windows.h> is exclusive to windows 
