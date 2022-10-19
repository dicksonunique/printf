Group project (Printf)

This printf project is a simple recreation of the printf function
Tasks:

0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life
mandatory
Write a function that produces output according to a format.

Prototype: int _printf(const char *format, ...);
Returns: the number of characters printed (excluding the null byte used to end output to strings)
write output to stdout, the standard output stream
format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:
c
s
%
You dont have to reproduce the buffer handling of the C library printf function
You dont have to handle the flag characters
You dont have to handle field width
You dont have to handle precision
You dont have to handle the length modifiers
Repo:
GitHub repository: printf
  
1. Education is when you read the fine print. Experience is what you get if you don't
mandatory
Handle the following conversion specifiers:

d
i
You dont have to handle the flag characters
You dont have to handle field width
You dont have to handle precision
You dont have to handle the length modifiers
Repo:
GitHub repository: printf
  
2. With a face like mine, I do better in print
#advanced
Handle the following custom conversion specifiers:
b: the unsigned int argument is converted to binary

Repo:
GitHub repository: printf
 
3. What one has not experienced, one will never understand in print
#advanced
Handle the following conversion specifiers:

u
o
x
X
You dont have to handle the flag characters
You dont have to handle field width
You dont have to handle precision
You dont have to handle the length modifiers
Repo:

GitHub repository: printf
  
4. Nothing in fine print is ever good news
#advanced
Use a local buffer of 1024 chars in order to call write as little as possible.

Repo:
GitHub repository: printf
  
5. My weakness is wearing too much leopard print
#advanced
Handle the following custom conversion specifier:

S : prints the string.
Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)

Repo:
GitHub repository: printf
 
6. How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print
#advanced
Handle the following conversion specifier: p.

You dont have to handle the flag characters
You dont have to handle field width
You dont have to handle precision
You dont have to handle the length modifiers
Repo:
GitHub repository: printf
  
7. The big print gives and the small print takes away
#advanced
Handle the following flag characters for non-custom conversion specifiers:

+
space
#
Repo:
GitHub repository: printf
  
8. Sarcasm is lost in print
#advanced
Handle the following length modifiers for non-custom conversion specifiers:

l
h
Conversion specifiers to handle: d, i, u, o, x, X

Repo:
GitHub repository: printf
  
9. Print some money and give it to us for the rain forests
#advanced
Handle the field width for non-custom conversion specifiers.

Repo:
GitHub repository: printf
  
10. The negative is the equivalent of the composer's score, and the print the performance
#advanced
Handle the precision for non-custom conversion specifiers.

Repo:
GitHub repository: printf
  
11. It's depressing when you're still around and your albums are out of print
#advanced
Handle the 0 flag character for non-custom conversion specifiers.

Repo:
GitHub repository: printf
  
12. Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection
#advanced
Handle the - flag character for non-custom conversion specifiers.

Repo:
GitHub repository: printf
  
13. Print is the sharpest and the strongest weapon of our party
#advanced
Handle the following custom conversion specifier:

r : prints the reversed string
Repo:
GitHub repository: printf
  
14. The flood of print has turned reading into a process of gulping rather than savoring
#advanced
Handle the following custom conversion specifier:

R: prints the rot13'ed string
Repo:
GitHub repository: printf
  
15. *
#advanced
All the above options work well together.

Repo:
GitHub repository: printf


Files
arg_nbr_functions.c & arg_nbr_functions_1.c
This file corresponds to every functions used to manipulate number arguments.

arg_str_functions.c
This file corresponds to every functions used to maninipulate string argument.

conversion.c
This file corresponds to every functions used to convert number, string, pointer.

int convert_alpha_numeric(int nb, int upper)
char *convert_base(unsigned long nb, unsigned int base, int upper)
char *convert_base_pointer(void *p)
char *convert_rot13(char *str)
numbers.c
This file corresponds to every basic number functions.

int print_unsigned_number(unsigned int n)
int print_number(int n)
int _nbr_len(int prmNumber)
char *_itoa(int prmNumber)
strings.c
This files corresponds to every basic string functions.

int _putchar(char c)
int _puts(char *str, int ascii)
int _strlen_recursion(char *s)
char *_strdup(char *str)
