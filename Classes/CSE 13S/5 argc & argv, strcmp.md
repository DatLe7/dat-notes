### Date: 04-11-2025 & 04-14-2025
### Instructor: Kerry Veenstra


## Notes:

### argc & argv
``` c
int main(int argc, char **argv) {}
```
- argc tells us the amount of arguments which includes the program itself
``` c
./args abc def
argc == 3
argv[0] is "./args"
argv[1] is "abc"
argv[2] is "def"
```
- You can use a for loop & printf to print through all the arguments
- Use the printf("%s", argv$[i]$) to do format string

### strcmp()
Stands for "String Compare"
- Part of String Library
``` c
#include <stdio.h>  
#include <string.h>  

int main(void) {  
printf("a,a: %d\n", strcmp("a", "a"));  
printf("a,b: %d\n", strcmp("a", "b"));  
printf("b,a: %d\n", strcmp("b", "a"));

return 0;  
}
```
**Alphabetical String Comparison**
- strcmp(s, t) == 0 means s same as t
- strcmp(s, t) < 0 means s before t
- strcmp(s, t) > 0 means s after t

### %.13f
``` c
#include <stdio.h>  

int main(void) {  
printf("!%f!\n", 1.23456789); // 6 decimals  
printf("!%13f!\n", 1.23456789); // right justify  
printf("!%-13f!\n", 1.23456789); // left justify  
printf("!%.13f!\n", 1.23456789); // 13 decimals  
printf("!%20.13f!\n", 1.23456789);  
return 0;  
}
```
**Output**
``` c
!1.234568!
!     1.234568!
!1.234568     !
!1.2345678900000!
!     1.2345678900000!
```
- %13f means 13 decimals points minimum and right justify
- %-13f means 13 decimals points minimum and left justify
- It will print spaces if there are not enough decimal points
- %.13f means 13 decimals after the .
- %20.13f means 20 decimals points minimum and 13 decimals after the . and right justify

### Calculating Series
• Σ means a for loop  
• Declare a sum variable  
• Maybe declare numerator and denominator  
• For each variable, ask  
1. What is the initial value?  
2. What is the iterative step?

### Integer Division vs Float Division
``` c
int i = 1;
int j = 2;
i / j // This will result in 0 b/c they are both ints

double z = 2.0;
i / z // This will result in 1/2 b/c atleast one of them is a float
```
