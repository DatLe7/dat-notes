### Date: 3-5-2025
### Instructor: Marcelo Siero


## Notes:
### Control Flow in RISC-V
![[Pasted image 20250316141503.png]]
- jal jumps and saves the return address into the PC (saves PC+4) which is the next instruction after the jal call
- When you do ret it changes the pc register to have the value stored in ra register (return address
![[Pasted image 20250316141640.png]]

### Data Flow in RISC-V
#### Leaf vs Non-Leaf Functions
![[Pasted image 20250316141711.png]]
- leaf functions are ones that never call other functions in its body
- non-leaf functions call other functions in its code body

#### Nested Functions
![[Pasted image 20250316141806.png]]
- The return address would be messed up when calling other functions inside a nested functions and would mess up the program

### Saving Registers
![[Pasted image 20250316141849.png]]
![[Pasted image 20250316141859.png]]
### Good Saving Practice
![[Pasted image 20250316141933.png]]
- when you are a leaf function you want to mainly use t or a registers because you do not have to save and load those registers
- as a nested function you want to be mainly using s registers because you don't have to save and load them for every function call like you do with t registers
### Register Saving Summary
![[Pasted image 20250316142104.png]]

### The Stack
![[Pasted image 20250316142122.png]]
![[Pasted image 20250316142147.png]]
**Saving 2 bytes on the stack example**
![[Pasted image 20250316142213.png]]

### Pushing Elements
![[Pasted image 20250316142248.png]]

### Accessing and Popping Elements
![[Pasted image 20250316142307.png]]

### Optimization Strategy
![[Pasted image 20250316142401.png]]
![[Pasted image 20250316142408.png]]

### Optimization Strategy for Leaf Functions
![[Pasted image 20250316142433.png]]

### Passing more than 8 arguments
![[Pasted image 20250316142504.png]]
- When there are too many arguments the stack may be used to store the arguments
