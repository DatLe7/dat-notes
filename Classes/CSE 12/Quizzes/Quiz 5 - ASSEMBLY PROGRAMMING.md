
1.) Which of the following commands multiplies the contents of register a2 by 8?
![[Pasted image 20250317122144.png]]
- shit left multiplies the expression by 2^n 

2.) What is the difference between a register and a memory location?
![[Pasted image 20250317122448.png]]

3.) Select the answer below which is true:
![[Pasted image 20250317122554.png]]

4.) In RISC-V assembly, what does the `jal` instruction do?
![[Pasted image 20250317122621.png]]

5.) What does the `ecall` instruction do in RISC-V assembly language?
![[Pasted image 20250317122831.png]]

6.) What is the difference between a RISC and a CISC instruction set?
![[Pasted image 20250317122848.png]]

7.) What does the `sw` instruction do in RISC-V assembly language?
![[Pasted image 20250317122915.png]]

8.) Consider the following RISC-V code snippet:
![[Pasted image 20250317122951.png]]

9.) Consider the following RISC-V code snippet:
![[Pasted image 20250317123015.png]]

10.) Given the following RISC-V assembly code:
![[Pasted image 20250317123035.png]]

11.) Consider the following RISC-V code snippet:
![[Pasted image 20250317123058.png]]

12.) Suppose we have the following stack, where the red line is the indicator for sp:
Suppose we now want the stack to contain these additional data items in the following order:
...Which of the following **sequence** of RISC-V instructions  will generate the stack status we want?
![[Pasted image 20250317123124.png]]
![[Pasted image 20250317123133.png]]

13.) Consider 6 functions f1, f2, f3, f4, f5, f6 residing in the RISC-V Main memory at different addresses. Let each function have its own separate author and that no author can view each other's work apart from the one written by themselves. All authors agree to adhere to RISC-V guidelines for saving/restoring registers to/from stack memory.
![[Pasted image 20250317123228.png]]

14.) A nested function calls another function (plot_function with parameter a0) and is also called by some function.  Given the code that follows  RISC-V calling convention, which sets of registers must be saved **to make this program function properly**.
![[Pasted image 20250317123355.png]]
![[Pasted image 20250317123411.png]]

15.)You are writing **a nested function,** that is , it serves both both a caller, and a callee.   You do not know much  about neither the caller nor about the callee functions it calls.  The function requires the use of some values that need to be preserved  throughout the body of your function.  Which of these types of RISC-V registers would be most desirable to use in order to store and access these values, given that the RISC-V register saving conventions are being followed.
![[Pasted image 20250317123445.png]]

16.) You are writing a leaf function. You have quite a few values you may want to preserve throughout the lifetime of your function.  What set of registers would you prioritize to use for this purpose, in order to reduce the total number of registers memory saving operations needed assuming that RISC-V register saving conventions are being followed?
![[Pasted image 20250317123515.png]]

17.) In the C programming language and in some others any integer value other than 0 is considered to be a "True", but bit-wise boolean operators such as "&" can provide surprising different results as compared to boolean operators such as: "&&" when used with this definition of truth.  The RISCV set conditional instructions are intended to deal with these differences. Please answer, which of these answers you feel is correct:
![[Pasted image 20250317123637.png]]
![[Pasted image 20250317123647.png]]

18.) Given the previous question which code snippet would best match this C code:
![[Pasted image 20250317123707.png]]
![[Pasted image 20250317124015.png]]