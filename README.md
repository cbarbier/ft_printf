# FT_PRINTF
Implementation of the famous printf function using VAR_ARGS with most of its flags.
## Prototype
```int ft_printf(const char *format, ...);```
## Flags
Any of these specifiers following a percent will be interpreted.\
Also between the percent and specifiers many flags can be set to modify the length | precision | prefix | padding ...
\
```%[-+ #0][\d\*][hh|h|ll|l|j|z][%sSdDioOuUxXcCbBfF]```

1. `%` print the character `'%'`.
1. `s` print the string at the address given.
1. `S` print the string with unicode at the address given
1. `p` print the address in hexadecimal.
1. `d` print the integer in base 10
1. `D` same as `d`.
1. `i` same as `d`.
1. `o` print the integer in base 8
1. `O` same as `o`.
1. `u` print the unsigned integer in base 10.
1. `U` same as `u`.
1. `x` print the integer in base 16.
1. `X` same as `x` but capitalize the letters.
1. `c` print the character.
1. `C` print the unicode character.
1. `b` print the integer in base 2.
1. `B` same as `b`
1. `f` print the float number.
1. `F` same as `f`.
