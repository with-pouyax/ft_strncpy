# ft_strncpy


This repository hosts the `ft_strncpy` function, a custom implementation designed for safe string copying operations in C. By limiting the number of characters copied from the source string to the destination buffer, `ft_strncpy` provides an essential tool for managing string data within predefined buffer sizes, enhancing both the functionality and security of string manipulation tasks.

## Description

`ft_strncpy` copies up to `n` characters from the string `src` to `dest`, stopping early if a null terminator is encountered in `src`. If the length of `src` is less than `n`, additional null bytes are appended to `dest` to ensure that a total of `n` characters are written. This behavior is crucial for creating strings that are exactly `n` characters long, regardless of the original length of `src`.
