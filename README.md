
# Libft - Library of Functions

## Introduction
Libft is a project where you will create a library of functions. The file structure for this project typically includes:

1. **.c Files**: These files contain the implementation of all your functions.
2. **.h (Header)**: The header file serves two main purposes:
   - Instead of including libraries like `<unistd.h>` in each `.c` file, you can include it once in your header file, and all your `.c` files will inherit it.
   - If one `.c` file calls a function from another `.c` file, you don’t need to write the function’s code in every file. Instead, just include `"libft.h"`, which will link the function definitions from the header.

   Make sure to include `#include "libft.h"` in all your `.c` files.

3. **Makefile**: The Makefile is used to automate the compilation process. Unlike in the piscine, where you had to manually compile your projects using `gcc` and `int main`, a Makefile allows you to compile everything by simply typing `make`. Once you've created the Makefile, it handles everything for you.

   **Great Resource for Libft**: [Libft Guide](https://www.asidesigned.com/project-libft.html)

## Libft Functions

### Functions from `<ctype.h>`:
- **ft_isalpha**: Checks if a character is alphabetic.
- **ft_isdigit**: Checks if a character is a digit (0–9).
- **ft_isalnum**: Checks if a character is alphanumeric.
- **ft_isascii**: Checks if a character is within the ASCII set.
- **ft_isprint**: Checks if a character is printable.
- **ft_toupper**: Converts a character to uppercase.
- **ft_tolower**: Converts a character to lowercase.

### Functions from `<string.h>`:
- **ft_memset**: Fills memory with a constant byte.
- **ft_strlen**: Calculates the length of a string.
- **ft_bzero**: Zeros a byte string.
- **ft_memcpy**: Copies a memory area.
- **ft_memmove**: Moves a memory area.
- **ft_strlcpy**: Copies a string with a specified size.
- **ft_strlcat**: Concatenates a string with a specified size.
- **ft_strchr**: Locates a character in a string.
- **ft_strrchr**: Locates the last occurrence of a character in a string.
- **ft_strncmp**: Compares two strings.
- **ft_memchr**: Scans memory for a character.
- **ft_memcmp**: Compares memory areas.
- **ft_strnstr**: Locates a substring in a string.
- **ft_strdup**: Creates a duplicate of a string.

### Functions from `<stdlib.h>`:
- **ft_atoi**: Converts a string to an integer.
- **ft_calloc**: Allocates memory and sets its bytes to 0.

### Non-standard Functions:
- **ft_substr**: Returns a substring from a string.
- **ft_strjoin**: Concatenates two strings.
- **ft_strtrim**: Trims characters from the beginning and end of a string.
- **ft_split**: Splits a string by a given delimiter.
- **ft_itoa**: Converts an integer to a string.
- **ft_strmapi**: Applies a function to each character of a string.
- **ft_striteri**: Applies a function to each character of a string.
- **ft_putchar_fd**: Outputs a character to a file descriptor.
- **ft_putstr_fd**: Outputs a string to a file descriptor.
- **ft_putendl_fd**: Outputs a string to a file descriptor followed by a newline.
- **ft_putnbr_fd**: Outputs a number to a file descriptor.

### Linked List Functions:
- **ft_lstnew**: Creates a new list element.
- **ft_lstadd_front**: Adds an element at the beginning of the list.
- **ft_lstsize**: Counts the number of elements in the list.
- **ft_lstlast**: Returns the last element of the list.
- **ft_lstadd_back**: Adds an element to the end of the list.
- **ft_lstclear**: Deletes and frees the list.
- **ft_lstiter**: Applies a function to each element of the list.
- **ft_lstmap**: Applies a function to each element of the list.

