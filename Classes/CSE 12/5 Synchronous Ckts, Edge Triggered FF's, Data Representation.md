### Date: 01-27-2025
### Instructor: Marcelo Siero


## Notes:

### Positive Edge Triggered D Flip Flops
![[Pasted image 20250202132500.png]]
- Only changes the value of Q to D when CLK goes from 0 to 1
![[Pasted image 20250202132534.png]]

### Negative Edge Triggered D Flip Flop
![[Pasted image 20250202132555.png]]
- Only changes the value of Q to D when CLK goes from 1 to 0
![[Pasted image 20250202132716.png]]

### Edge Triggered M/S D F/Fs are Made from 2 D-Latches
![[Pasted image 20250202132744.png]]
- The first D-Latch locks keeping the value of D at the moment when CLK changes value and then the second D-Latch opens changing the value of Q to the value of D when the CLK value changes
- They have a master slave dynamic
![[Pasted image 20250202133013.png]]
- This is a positive edge triggered flip flop because when it goes from 0 to 1. The first D-Latch locks and passes the value to the second D-Latch

### Synchronous Clocks
![[Pasted image 20250202133446.png]]
- The register can only register a new 8 bit value when the clock goes to 1
![[Pasted image 20250202133539.png]]
- This is a 8-bit shift register because it has 8 D-Latches that hole a bit value and every time the CLK becomes 1 the input is given to the leftmost bit and everything is shifted left.
![[Pasted image 20250202133657.png]]
- This is a counter because the adder takes the value of the 8-bit register and adds to it and makes that the new value of the register
![[Pasted image 20250202133744.png]]

### Data Representation
![[Pasted image 20250202134046.png]]
- The amount of things a N amount of bits can represent in binary is $2^N$
![[Pasted image 20250202134121.png]]

### Character Representation
![[Pasted image 20250202134227.png]]

#### Integer Representation
*Usual answers:*

1. Represent 0 and consecutive positive integers
	• Unsigned integers

2. Represent positive and negative integers
	• Signed magnitude
	• One’s complement
	• Two’s complement

*Unsigned and two’s complement the most common*

#### Unsigned Integers
![[Pasted image 20250202135242.png]]
- Your normal binary representation of integers but can only range from positive integers

#### Signed Integers
![[Pasted image 20250202135400.png]]
- Signed integers are able to represent negative number but its magnitude of number able to be represented for the same amount of bits is half of unsigned integers
- The first bit represents if the integer is positive or negative
- You cannot do binary addition to represent subtraction, So 3 + (-3) would result in -5
![[Pasted image 20250202135909.png]]
#### One's Complement
![[Pasted image 20250202140027.png]]
- The first bit tells you if the integer is positive or negative and the rest is the binary representation but flipped
- So -1 is represented by 1110 where the first 1 means its negative and the last 3 are the flipped binary representation of 1 (001 to 110)
- Unlike signed integer we are able to do binary addition
![[Pasted image 20250202140256.png]]
- The only problem is that there are two binary representations for 0 (1111 or 0000) negative and positive 0
#### Twos Complement
![[Pasted image 20250202140547.png]]
![[Pasted image 20250202140605.png]]
- Twos complement is taking ones complement then adding 1
- This solves the problem with two representations of 0
*To find the value of a twos complement representation* 
![[Pasted image 20250202140746.png]]
- Binary Addition also works
![[Pasted image 20250202140844.png]]
![[Pasted image 20250202141334.png]]

### Ranges
*n is the number of bits*
1. Unsigned Integers: 0 to $2^{n-1}$
2. Signed Integers: -($2^{n-1}$) to $2^{n-1}$
3. One's Complement: -($2^{n-1}-1$) to $2^{n-1}-1$
4. Two's Complement: -($2^{n-1}$) to $2^{n-1}-1$

### Sign Extension
*This is the name of a technique used to change a signed number with a smaller number of bits into the same number (and same representation) with a larger number of bits?*
![[Pasted image 20250202141537.png]]

![[Pasted image 20250202141615.png]]

![[Pasted image 20250202141626.png]]
![[Pasted image 20250202141649.png]]