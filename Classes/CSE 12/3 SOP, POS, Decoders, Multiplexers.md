### Date: 01-22-2025
### Instructor: Marcelo Siero


## Notes:

### Definitions
![[Pasted image 20250122195121.png]]

### Sum Of Products
![[Pasted image 20250122195141.png]]
- Canonical means that it is in its original form with all its terms and has not been simplified at all
![[Pasted image 20250122195230.png]]
- When doing SOP we look at inputs with 1
- Minterm is the product(multiplication) of inputs that would allow for that row to input true
![[Pasted image 20250122195402.png]]
#### EXAMPLE
![[Pasted image 20250122195608.png]]

### Product Of Sums
![[Pasted image 20250122195429.png]]
- Maxterm is a sum(addition) of inputs where it is the only way for that row to be false

#### EXAMPLE
![[Pasted image 20250122195624.png]]
![[Pasted image 20250122195705.png]]
- Sum of Products uses OAI
- Product of Sums uses AOI
![[Pasted image 20250122195809.png]]
![[Pasted image 20250122195850.png]]
![[Pasted image 20250122195927.png]]

### XOR Gate
![[Pasted image 20250122200007.png]]

### Decoders
![[Pasted image 20250122200235.png]]
![[Pasted image 20250122200302.png]]
![[Pasted image 20250122200344.png]]
- Decoders only input 1 HIGH output at once
- Decoders can be used to turn binary into decimal

### Multiplexers
![[Pasted image 20250122200429.png]]
- Selects one of the inputs to be sent out as the outputs and ignores the rest of the inputs
![[Pasted image 20250122200509.png]]
![[Pasted image 20250122200548.png]]
- S in this case is a binary number choosing inputs 0-3
![[Pasted image 20250122200633.png]]
- Multiplexers come in variables of $2^n$ because S represents a binary number

### Logical Completeness and Universal Gates
![[Pasted image 20250122200751.png]]
- You can make ANY truth table with either only NAND or only NOR

- Sum of Products and Product of Sums can be simplified using some of the theorems of Boolean Algebra