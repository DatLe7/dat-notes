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

