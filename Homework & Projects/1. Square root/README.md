## Homework: Several Square Roots
Modify the square root program to compute and print the square root of all arguments to the program.  There
may be zero arguments.  You can use `argc`, or you can watch for the `NULL` pointer in `argv` to iterate through the
list, but watch out for registers being clobbered by the functions you call!  Call your program `sqrt_list`.

```
$ sqrt_list
$ sqrt_list 16 9 65536 2
sqrt(16.000000) = 4.000000
sqrt(9.000000) = 3.000000
sqrt(65536.000000) = 256.000000
sqrt(2.000000) = 1.414214
```
There are three different solutions in this folder as follow:
1. `sqrt_list.asm`: Takes multiple arguments and return the square root of each by looking out for the terminating null pointer
2. `sqrt_list_c.asm`: Takes multiple arguments and return the square root of each using a counter
2. `sqrt.asm`: takes a single argument and return its corresponding square root
