### Date: 01-29-2025
### Instructor: Marcelo Siero


## Notes:

### Logical and Arithmetic Shifts
![[Pasted image 20250204153921.png]]

#### Logical Shift Right
- Logical shift right by n
	• Moves bits n times to the right in order
	• Throws away the bit/s that pops off the LSB
	• Introduces 0’s into the MSB (left) side
- This is a inexpensive way to divide unsigned integers by powers of 2

#### Logical Shift Left
- Logical shift left by N
	• Move bits to the left in order by N
	• Throw away the bit/s that pops off from the MSB
	• Introduce 0’s into the LSB (right side)
- This is a inexpensive way to multiply unsigned integers by powers of 2

### Arithmetic Shifts (for signed numbers)

#### Arithmetic Right Shifts
- Arithmetic right shift by N
	● Move all bits to the right N times
	● Throw away the bit/s that pop off the LSB
	● Copy the original Sign bit (MSB) into all the available spaces on the left. (which preserves the sign)
- Logical and Arithmetic right shifts are an inexpensive way to divide a signed integer by powers of 2:
- This is floor division so it will always round towards -infinity
#### Arithmetic Shift Left
- Arithmetic shift left by N
	● Move bits to the left in order by N
	● Throw away the bit/s that pop off the MSB
	● Introduce a 0 into the LSB
- Logical and Arithmetic left shift is an inexpensive way to multiply a signed integer by powers of 2:
- If the products sign changes then that means their was an overflow

### Rotates

#### Rotate Left
- Rotate left
	● Move bits to the left in order
	● Put the bit(s) that pop off the MSB into the LSB
	● No bits are thrown away or lost

#### Rotate Right
- Rotate right
	● Move bits to the right, same order
	● Put the bit that pops off the LSB into the MSB
	● No bits are thrown away or lost

### Integer Number Bases: Binary vs. Other Bases

![[Pasted image 20250204155019.png]]
- Select a number as the base b
- Define an alphabet of b–1 symbols plus a symbol for zero to represent all numbers
- Use an ordered sequence of 1 or more digits d to represent numbers
- The represented number is the sum of all digits, each multiplied by b to the power of the digit’s position i
![[Pasted image 20250204155115.png]]

#### Number Systems
![[Pasted image 20250204155137.png]]
![[Pasted image 20250204155154.png]]
![[Pasted image 20250204155204.png]]

### Base Conversions: Between Binary, Octal and Hex
![[Pasted image 20250204155309.png]]

#### Binary To Octal Conversion
![[Pasted image 20250204155518.png]]
![[Pasted image 20250204155552.png]]'

#### Octal To Binary Conversion
![[Pasted image 20250204155708.png]]
![[Pasted image 20250204155714.png]]

#### Binary To Hex Conversion
![[Pasted image 20250204155735.png]]
- like converting to octal but uses 4 bits instead of 3
![[Pasted image 20250204155800.png]]

#### Decimal To Binary Conversion
![[Pasted image 20250204160127.png]]
![[Pasted image 20250204160150.png]]

### More General Base Conversions
1. From any base b to base 10
2. From base 10 to any base b
3. From any base b to any other base c

![[Pasted image 20250204160334.png]]![[Pasted image 20250204160348.png]]



![[Pasted image 20250204160403.png]]
![[Pasted image 20250204160535.png]]
![[Pasted image 20250204160543.png]]
![[Pasted image 20250204160552.png]]
![[Pasted image 20250204160558.png]]

### Random Facts
![[Pasted image 20250204160723.png]]
![[Pasted image 20250204160743.png]]
