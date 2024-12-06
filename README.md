# Libft - Your First C Library

Libft is a foundational project at 42 that challenges you to reimplement some of the most commonly used C library functions and expand upon them with additional functionality. This custom library serves as a building block for future projects.

## 🚀 Features

### Mandatory Part
- **Libc Functions:** Reimplemented standard C library functions, including:
  - Character checks: `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
  - String operations: `ft_strlen`, `ft_strchr`, `ft_strncmp`, `ft_strnstr`
  - Memory management: `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`
  - Conversion: `ft_atoi`, `ft_toupper`, `ft_tolower`
  - Dynamic allocation: `ft_calloc`, `ft_strdup`

- **Additional Functions:**
  - String manipulation: `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`
  - Conversion: `ft_itoa`
  - Iteration: `ft_strmapi`, `ft_striteri`
  - File descriptor outputs: `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### Bonus Part
- **Linked List Utilities:** Manage linked lists with functions like:
  - Node creation: `ft_lstnew`
  - List manipulation: `ft_lstadd_front`, `ft_lstadd_back`, `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`
  - List information: `ft_lstsize`, `ft_lstlast`

## 🛠️ Technical Details
- Written in **C**.
- Follows the [42 Norm](https://github.com/42School/norminette).
- No memory leaks: All dynamically allocated memory is properly freed.
- Library compiled into `libft.a` using `ar`.

## 📂 Files and Structure
- **Source Files:** `ft_*.c`
- **Header File:** `libft.h`
- **Makefile:** Includes rules for `all`, `clean`, `fclean`, `re`, and `bonus`.

## 🔧 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/pleiadeslol/42_Libft.git
   cd 42_Libft
