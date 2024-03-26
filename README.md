# ft_printf

![ft_printf Logo](https://yourimagehost.com/your-ft_printf-logo.png)

Hey there! Welcome to my ft_printf project! 🚀 As a student at 42 Berlin, I embarked on the challenge of recreating the `printf` function from scratch. This project is not just about mimicking a function; it's about understanding variadic functions and format specifiers, essential skills for any C programmer.

---

## About
ft_printf isn't just another coding assignment; it's a journey of discovery and learning. In this project, I've tackled the task of implementing my version of the `printf` function, named `ft_printf`. Through this endeavor, I've deepened my understanding of variadic functions and the intricacies of format specifiers.

---

## Project Requirements
- **Program name:** libftprintf.a
- **Turn in files:** Makefile, *.h, */*.h, *.c, */*.c
- **Makefile:** NAME, all, clean, fclean, re
- **External functions:** malloc, free, write, va_start, va_arg, va_copy, va_end
- **Libft authorized:** Yes

---

## Functionality
My `ft_printf` function mirrors the functionality of the original `printf` function and includes the following format specifiers:
- **%c:** Prints a single character.
- **%s:** Prints a string (as defined by the common C convention).
- **%p:** Prints a void * pointer argument in hexadecimal format.
- **%d:** Prints a decimal (base 10) number.
- **%i:** Prints an integer in base 10.
- **%u:** Prints an unsigned decimal (base 10) number.
- **%x:** Prints a number in hexadecimal (base 16) lowercase format.
- **%X:** Prints a number in hexadecimal (base 16) uppercase format.
- **%%:** Prints a percent sign.

---

## Usage
To use my `ft_printf` function, follow these steps:
1. Clone this repository to your local machine.
2. Navigate into the project directory.
3. Compile the `libftprintf.a` library by running `make`.
4. Include the header file `ft_printf.h` in your source files.
5. Link `libftprintf.a` to your projects.
6. Start using `ft_printf` just like you would use `printf` in your C programs!

Example:
```c
#include "ft_printf.h"

int main() {
    ft_printf("Hello, %s!\n", "world");
    return 0;
}
