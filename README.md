_printf page_facing_up

A formatted output conversion C program completed as part of the low-level programming and algorithm track at Holberton School. The program is a pseudo- recreation of the C standard library function, printf.

Dependencies couple

The _printf function was coded on an Ubuntu 14.04 LTS machine with gcc version 4.8.4.

Usage runner

To use the _printf function, assuming the above dependencies have been installed, compile all .c files in the repository and include the header main.h with any main function.

Example main.c:

#include "holberton.h"

int main(void)
{
    _printf("Hello, Apam and Jonas");

    return (0);
}

Compilation:

$ gcc *.c -o tester

Output:

$ ./tester
Hello, World!
$

Description speech_balloon

The function _printf writes output to standard output. The function writes under the control of a format string that specifies how subsequent arguments (accessed via the variable-length argument facilities of stdarg) are converted for output.

Prototype: int _printf(const char *format, ...);
Return Value

Upon successful return, _printf returns the number of characters printed (excluding the terminating null byte used to end output to strings). If an output error is encountered, the function returns -1.
