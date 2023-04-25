# C - Custom printf function

## Background Context
```
Custom printf function
```
![printf](https://user-images.githubusercontent.com/85158665/213859591-8d8dbbb1-2be7-4f75-ae00-cc1b66dda46c.png)
## Requirements
### General
* Used editors: `vi`, `vim`
* All files will compiled on Ubuntu 20.04 LTS using gcc, using the options `-Wall -Werror -Wextra -pedantic -std=gnu89`
* All files end with a new line
* Code for custom printf uses the `Betty` style. Checked using [betty-style.pl](https://github.com/holbertonschool/Betty/blob/master/betty-style.pl) and [betty-doc.pl](https://github.com/holbertonschool/Betty/blob/master/betty-doc.pl)
* No global variables used
* No more than 5 functions per file
* The prototypes of all your functions are included in header file called [main.h](./main.h)
* All header files are include guarded
## More Info
### Global functions and macros used
* `write` (man 2 write)
* `malloc` (man 3 malloc)
* `free` (man 3 free)
* `va_start` (man 3 va_start)
* `va_end` (man 3 va_end)
* `va_copy` (man 3 va_copy)
* `va_arg` (man 3 va_arg)
## Compilation
```
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c
```

## Task 0 
Write a function that produces output according to a format.  

### Prototype: *```int _printf(const char \*format, ...);```*

Returns: the number of characters printed (excluding the null byte used to end output to strings).  
write output to stdout, the standard output stream  
format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:  
c  
s   
%  
You don’t have to reproduce the buffer handling of the C library printf function.  
You don’t have to handle the flag characters.  
You don’t have to handle field width.  
You don’t have to handle precision.  
You don’t have to handle the length modifiers.  
## Task 1
Handle the following conversion specifiers: d & i
## Task 2
Handle the following conversion specifiers: b
