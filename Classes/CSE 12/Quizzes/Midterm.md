1.) Answer all that apply to this circuit.
![[Pasted image 20250316114052.png]]
- This does not implement a shift register because Z
- This is not a combinational circuit, as it can store data.
- This **IS** a circuit that implements a pass-thru D-Latch because
- This circuit does use full transmission gates because both the inputs A and A' are passed.

2.) Suppose decimal integer x=17 is expressed in binary using 12 bits. What are the corresponding results (in decimal) of the two logical shifts,   x << 4  = ?   and    x >> 3 = ?
**The following options are all represented in base 10. You must only choose the option in which both shifts are done correctly - no partial credit.**
![[Pasted image 20250317115542.png]]

3.)In this  circuit the CK being high implies that the latch will pass the value of that latch through to its outputs, low implies that the latch will hold whatever value was last presented to its D input during the 1 to 0 transition of CK.    What type of device is this?
![[Pasted image 20250317115724.png]]

4.) The following diagram shows the inputs to a D flip flop (**negative edge** trigger)
![[Pasted image 20250317115745.png]]
- 0 is incorrect because this is a ***negative*** edge trigger, so it gets the new value of 1 right before time t, so its 1. 

5.) What is the **Sum of Products** solution for the following truth table?  Select all that apply.
![[Pasted image 20250317115934.png]]

6.) Sign extending the 8-bit 2's Complement number 0x83 results into a 16-bit number results in this:
![[Pasted image 20250317115957.png]]

7.) Your team needs to make a logic circuit that compares four 2-bit numbers, and outputs ”1” if and only if the four numbers are identical. Your teammate proposes making a truth table for every possible combination of the inputs. How many rows would be in this truth table?
![[Pasted image 20250317120024.png]]

8.) Suppose we have **k different inputs**, and we want to use a multiplexer with an **s-bit** selector to output one of the inputs.

Which of the following setup will **not** work? Select all that apply.
![[Pasted image 20250317120044.png]]

9.) 0xA0 is an 8-bit 2’s complement number.  What base 10 integer does it represent?
![[Pasted image 20250317120107.png]]

10.) An NMOS Device is more effective at transferring a "1" than a "0" value.
![[Pasted image 20250317120149.png]]

11.) What type of Circuit is this (answer all that apply):
![[Pasted image 20250317120222.png]]
- I will not be fooled again... you can use demorgans law on this circuit to make it a different one (sop)

12.) Which of the following 8-bit 2’s complement calculations overflows? Select all that apply.
![[Pasted image 20250317120331.png]]
- Overflow occurs when the sign bit changes in addition or shifts when it is NOT supposed to. This flips a 2's complement positive number to a negative or vise-versa.
- 1100 1001 + 1100 0011 is **FALSE** bc the sign bit will actually stay the same, even if at first glance it looks like there will be one.
- 0101 0011 + 0101 1000 is true because an overflow happens or whatever

13.) Select the Boolean expressions(all that apply) that share the same truth table as  
**A'B'C' + AB'C' + AB'C**
![[Pasted image 20250317120801.png]]
- (A +B + C')(A + B' +C).... is **CORRECT** because it is the **PROCUCT OF SUMS** version of the **SUM OF PRODUCTS** that we are given, meaning we will get the same truth table...
- (a+b+c).... uhhhh its wrong bc its wrong dumbass

14.) A 7-bit 2's complement number has a bit pattern that can be represented by the hex number 0x40.  Which of these statements can be said to be true about this number.
![[Pasted image 20250317121322.png]]

15.) Consider a 4 bit ripple carry adder with inputs A[3:0] =0110 and B[3:0]=1011. What are the results of full adder for bit 3?
![[Pasted image 20250317121342.png]]
- In the world of binary addition, 1 + 1 = ...0 (with a carry of 1...) **NOT** 1 w/ carry of 1.