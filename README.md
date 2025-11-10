## ft_printf @ 1337
This repository contains my implementation of the ft_printf project, a requirement at 1337 (42 Network). This project involves recoding the C printf() function.


The primary goal is to understand and implement one of C's most versatile functions, focusing on the challenge of handling a variable number of arguments.


## Project Overview
ft_printf takes a format string and a variable number of arguments, then writes the formatted output to stdout. This implementation is compiled as a static library, libftprintf.a, which can be linked to future C projects.



## Features Implemented
This version of ft_printf successfully implements both the mandatory and bonus parts of the subject.

Mandatory Conversions

%c - Prints a single character.


%s - Prints a string.


%p - Prints a void pointer's address in hexadecimal.


%d - Prints a signed decimal integer.


%i - Prints a signed decimal integer.


%u - Prints an unsigned decimal integer.


%x - Prints an unsigned hexadecimal (lowercase).


%X - Prints an unsigned hexadecimal (uppercase).


%% - Prints a literal percent sign.

## Bonus Features
This implementation also handles the following bonus flags, width, and precision modifiers:


Flags: - (left-justification) and 0 (zero-padding).


Flags: # (alternative form), (space), and + (always show sign).


Width: Minimum field width (e.g., %10d).


Precision: . (e.g., %.5s or %.3d).

## Key Concepts & Skills

Variadic Functions: Mastered the use of <stdarg.h> macros, including va_start, va_arg, va_copy, and va_end, to manage an indefinite number of arguments.

Format String Parsing: Developed a robust parser to read the format string, identifying and applying conversions, flags, and modifiers.


Code Structure: Focused on creating extensible and well-structured code to manage the project's complexity, as recommended by the subject.


Static Library Creation: Used the ar command to create the libftprintf.a static library, a fundamental skill for C development.
