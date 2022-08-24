# libft
The first project of 42 school
The aim of the project is to create basic functions of C library.

To compile the static library use make command. You can use this library by compiling your project with the library.
Declaratins of functions are represented in header file.

Here list of functions and brief description:

• ft_isalpha - check if a character is ASCII letter;

• ft_isdigit - check if a character is ASCII digit symbol;

• ft_isalnum - check if a character is ASCII letter or digit symbol;

• ft_isascii  - check if a character is ASCII;

• ft_isprint - check if a character is ASCII printable letter;

• ft_strlen - evaluate lentght of C-string;

• ft_memset - set value into 1-byte cells of memory for certaint amount of memory;

• ft_bzero - set zero value into 1-byte cells of memory for certaint amount of memory

• ft_memcpy - copy values from dst to src;

• ft_memmove - copy values from dst to src;

• ft_strlcpy - copy C-string from dst to src;

• ft_strlcat - copy C-string from dst to src;

• ft_toupper - make letter upper;

• ft_tolower - make letter lower;

• ft_strchr - find symbol in C-string;

• ft_strrchr - find symbol in C-string from the end;

• ft_strncmp - compare C-strings;

• ft_memchr - find something inmemory;

• ft_memcmp - compare values in memory;

• ft_strnstr - function locates the first occurrence of the null-terminated string;

• ft_atoi - makes int from C-string;

• ft_calloc - function allocates memory and set values to zero;

• ft_strdup - return allocated copy of C-string;

• ft_substr - allocates and returns a substring from the string;

• ft_strjoin - allocates and returns a new C-string, which is the result of the concatenation of two strings;

• ft_strtrim - cut strings from the begining and the end from another string and return allocated result;

• ft_split - split string to array of strings;

• ft_itoa - return int as allocated string;

• ft_strmapi - Applies the function ’f’ on each character of the string;

• ft_striteri - Applies the function ’f’ on each character of the string passed as argument;

• ft_putchar_fd - write a character to the file descriptor;

• ft_putstr_fd - write a string to the file descriptor;

• ft_putendl_fd - write a string to the file descriptor witn endl;

• ft_putnbr_fd - write a integer to the file descriptor;

Lst functions use struct:

typedef struct s_list
{
  void *content;
  struct s_list *next;
} t_list;

• ft_lstnew - creates a new allocated element t_list;

• ft_lstadd_front - add element to the beginning of chained list;

• ft_lstsize - return size of chained list;

• ft_lstlast - return last element of chainde list;

• ft_lstadd_back - add element to the end of list;

• ft_lstdelone - Takes as a parameter a node and frees the memory of the node’s content using the function ’del’ given as a parameter and free the node;

• ft_lstclear - Deletes and frees the given node and every successor of that node;

• ft_lstiter - Iterates the list and applies the function on the content of each node;

• ft_lstmap - Iterates the list and applies the function on the content of each node;
