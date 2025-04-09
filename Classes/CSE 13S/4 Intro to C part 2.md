### Date: 04-09-2025
### Instructor: Kerry Veenstra


## Notes:
### Arithmetic Operations 
![[Pasted image 20250409162914.png]]
![[Pasted image 20250409162925.png]]
![[Pasted image 20250409162932.png]]
![[Pasted image 20250409162943.png]]
![[Pasted image 20250409162953.png]]
- There are no objects in C but there are objects in C++

### While Loop
- A while loop is called a top-test loop
``` c
int i = 0; 
while (i < 3) { // while keyword and conditional
	... // body of the while loop
	i = i + 1; // iterator
}
```
**Three Ways to increment a counter (or decrement)**
``` c
int a = 0;
a = a + 1;
a += 1;
a++;
++a;
```
**Two ways to increment by more than 1**
``` c
int a = 0
a = a + 3;
a += 3;
```
**Two ways to scale a counter**
``` c
int a = 1;
a = a * 2;
a *= 2;
```

- If you have a nested while loop initialize the counter inside the first while loop

### For Loop
- A for loop is called a top-test loop
``` c
for (int i = 0; i < 3; i++){
	...
}
```
- Three expressions separated by a ; called the initializer, conditional and iterator
![[Pasted image 20250409163641.png]]
- You can also initialize the counter variable outside the for loop
``` c
int i;
for (i=0; i <= 3; i++){
	...
}
```
- I will have a final value of 4

### Do-while Loop
- A do-while loop is called a bottom-test loop
- A do-while loop will always run at least once
``` c
do {
	...
} while (something);
```

### n+1/2 loop
``` c
while (1) {
	...
	if (something) break;
	...
}
for (;;) {
	...
	if (something) break;
	...
}
```
- Infinite loop with a conditional break
- Having blank expression on the for loop will make it an infinite loop

**Example**
``` c
#include <stdio.h>

int main(void) {
	while (1) {
		int ch = getchar();
		if (ch == EOF) break;

		printf("%c", ch);
	}

	return 0;
}
```
- EOF is a constant value which means that the file ends. Stands for "end of file"
- When we call getchar() we put the return value into a int variable b/c EOF is outside the representable range of the char dtype because it can only store up to a unsigned 8bit number
- This is because EOP = -1 and characters are read with unsigned values
