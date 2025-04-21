### Date: 04-18-2025
### Instructor: Kerry Veenstra


## Notes:

### Assert
``` c
#include <assert.h>

assert(condition)
```
- Just like in python you put in a conditional if it is true nothing happens but if it is false then an assertation error is raised
- Part of the assert.h library

### ctype.h
``` c
#include <ctype.h>
#include <stdio.h>

if (islower(ch)) printf(" islower");
        if (isupper(ch)) printf(" isupper");
        if (isprint(ch)) printf(" isprint");
        if (isgraph(ch)) printf(" isgraph");
        if (ispunct(ch)) printf(" ispunct");
```
- Functions to determine the type of char
- Boolean functions
- Part of ctype.h library

### getchar
``` c
#include <stdlib.io>
int ch = getchar();
```
- Used to read text given to the program
- Must be given to an int because of EOF special char
- Part of standard library

### switch
``` c
switch (ch) {
	case 'a':
		++num_a;
		break;
	case 'b':
		++num_b;
		break;
	case 'c':
		++num_c;
		break;
	default:
		++num_other_characters;
		break;
}
```
- Jumps to the value that is the same as ch
- Will keep incrementing the pc / going to the next instruction so you must include a break statement
- If no value is found then default is run

