*This activity has been created as part of the 42 curriculum by sshakhat.*
#Get_Next_Line
## Description
get_next_line is a function that reads a line from a file descriptor, returning it as a string.
It handles multiple scenarios including files ending with or without newline characters, empty files, and reading from stdin.
# files


get_next_line.c – Main implementation

get_next_line.h – Header file with function prototypes

utils.c – Helper functions: ft_strlen, ft_strjoin, ft_strchr
## Utilities


size_t ft_strlen(const char *s) – Returns the length of a string.

char *ft_strjoin(char *s1, char *s2) – Joins two strings into a new allocated string.

char *ft_strchr(char *s, int c) – Returns a pointer to the first occurrence of a character in a string

## Resources
the following resources were used as references while working on this project:

- **man pages (Linux manual)**
  - man strlen, man strlcat, man memcpy, man memmove, man atoi, etc.
  Used to understand the exact behavior, return values, and edge cases of standard C functions.

- **The C Programming Language – Brian W. Kernighan & Dennis M. Ritchie**
  A classic reference for understanding core C concepts such as pointers, memory management, and strings.

- **42 Documentation**
  - Libft subject PDF
  - 42 Norm (coding style rules)
  Used to ensure compliance with project requirements and coding standards.

- **cplusplus.com**
  https://cplusplus.com/reference/cstring/
  Used to review function behavior and examples for string and memory functions.

- **GeeksforGeeks**
  https://www.geeksforgeeks.org/c-programming-language/
  Used for additional explanations and edge case discussions related to C functions and linked lists.

AI assistance was used as a **learning and support tool** during this project.

Specifically, AI was used to:
- Explain the behavior of C standard library functions (e.g., `strlcat`, `memmove`, `strnstr`)
- Clarify edge cases and common pitfalls
- Help understand linked list concepts in the bonus part
- Review logic and provide suggestions for cleaner and more readable implementations
- Assist in debugging and understanding compiler warnings

AI was **not used to blindly generate solutions**.
All code was manually written, reviewed, and adapted by the student to fully comply with the 42 Norm and project requirements.

The use of AI contributed to better understanding, not replacement of personal work.

