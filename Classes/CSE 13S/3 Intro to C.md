### Date: 04-07-2025
### Instructor: Kerry Veenstra


## Notes:
### Hello World
``` c
#include <stdio.h>

int main(void) {
	printf("hello, world\n");
	return 0
}
```
- int is the return type
- main is the function name
- (void) means zero parameters
- {} encloses the body of the function
- printf("hello, world\n") prints out hello, world then next line 
- return 0 tells the computer than the program successfully terminated

- Indentation does not matter to the computer but still write good code

**Printf()**
`prinf("%d", 42);`
- `"%d"` means format a integer here
- 42 is printed in the place of `"%d"`
`prinf("%d, hi %d", 42, 30);
### Compiling a C program
- You can edit the c file using vim or any other text editor
- You can compile the c file into an executable with the clang compiler
- if you don't opt to name the executable it will be title a.out
- do the command ./a.out 
- this will run the executable file. You need to use ./ to dictate that the executable is in the working directory

### Curly Braces
``` c
int a = 1, b = 1;
if (a < b)
	printf("a");
	printf("b");
printf("c");
// Result: bc
```
- b and c will be printed because there are no curly braces on the if statement the if statement only controls the immediate next statement

### Variable Declarations and Initialization
**Variable Declaration:**
``` c
type name;
type name = value;
type name1 = value1, name2 = value2,
// Examples
int x = 3;
int y = 4;
int x = 3, y = 4;
int x, y;
```
- It is good practice avoid declaring variable without initializing a value
**Assigning new values to a variable**
``` c
x = 3;
x = x + 1;
y = m * x + b;
```

### If Statement
``` c
if (conditional) {
	body
}
```
- start with the if keyword
- then have the conditional inside the parathesis (ex. `(x < 5)`)
- Then the body is the code that will be run if the conditional is true

- In C any non-zero value is perceived as true
``` c
if (10){} // this will be true
if (0){} // this will be false
if (-1){} // this will be true
```

**Equality and Relational Operators**
1. <
2. >
3. <=
4. >=
5. ==
6. !=

### Logical Or
``` c
// An or is represented by ||
if (a || b){ // The conditional will be true if a or b are true
 	return 0
}
```