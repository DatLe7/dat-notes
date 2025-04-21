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

### array
`int nums[5]`
- This will store 5 elements
`int nums[] = [2, 3, 5, 6,1, 1, 4]`
- C will automatically assign memory to the array if a value is initialized

``` c
#include <stdio.h>
#include <string.h>

char s1[4] = "abc";
char s2[] = "def"; // Will automatically assign 4 elements worth of memory

int main(void) {
    printf("s1 is %s\n", s1);
    printf("s2 is %s\n", s2);

    strncpy(s2, s1, 4);

    printf("s1 is %s\n", s1);
    printf("s2 is %s\n", s2);
    return 0;
}
```
- We can also leave the memory assignment blank and allow C to determine how much is needed
- Strings are just arrays of chars
- Strings need a terminating term with value 0
- So a string "ddd" with have 4 elements with the last one being value 0
