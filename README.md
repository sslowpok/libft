# libft 
First library with some recoded functions from libc and other external ones

# Functions from libc:
1. isalpha
2. isdigit
3. isalnum
4. isascii
5. isprint
6. strlen
7. memset
8. bzero
9. memcpy
10. memmove
11. strlcpy
12. strlcat
13. toupper
14. tolower
15. strchr
16. strrchr
17. strncmp
18. memchr
19. memcmp
20. strnstr
21. atoi
22. calloc
23. strdup

# Additional functions

## ft_substr (char *ft_substr(char const *s, unsigned int start, size_t len))
Its aim is to allocate a substring from a string.
## ft_strjoin (char *ft_strjoin(char const *s1, char const *s2))
Its aim is to allocate string made from 2 strings.
## ft_strtrim (char *ft_strtrim(char const *s1, char const *set))
Its aim is to allocate trimmed from left to right string. Chars that must bu trimmed are in set, given as argument.
## ft_split (char **ft_split(char const *s, char c))
Its aim is to split string with given separator and allocate array of resulting substrings.
## ft_itoa (char *ft_itoa(int n))
Its aim is to allocate string that is result of converting an integer, given as argument.
## ft_striteri (void ft_striteri(char *s, void (f)(unsigned int, char)))
Its aim is to aplly function given as argumnet to each character of a string.

# Bonus functions
## ft_lstnew
Allocates and returns a new element of list.
## ft_lstadd_front
Adds the element at the beginning of the list.
## ft_lstsize
Counts the number of elements in a list.
## ft_lstlast
Returns the last element of the list.
## ft_lstadd_back
Adds the element at the end of the list.
## ft_lstdelone
Frees the element given as a parameter, and free the content of the element using the function given as a parameter.
## ft_lstclear
Its aim is to aplly function given as argumnet to each content of the list.
## ft_lstiter
It's aim to aplly function given as argumnet to each content of the list.
## ft_lstmap
It's aim to aplly function given as argumnet to each content of the list. It returns new list resulting from succesive application of a function.

