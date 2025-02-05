### Date: 02-03-2025
### Instructor: Jiayin Pan


## Notes:

### Elementary Matrices
An Elementary Matrix is a square matrix (nxn) obtained by applying an elementary  row operation to $I_{n}$
![[Pasted image 20250205080416.png]]

### Observation
- If $A\in M_{mxn}$. If E is a mxm elementary matrix obtained by some elementary row operation, Then $E\cdot A$ is the matrix obtained by the same row operation applied to A
![[Pasted image 20250205080603.png]]

### Correlation
- In particular, if $A\in M_{mxn}$ is invertible (i.e. its RREF is $I_{n}$) then ($E_{k}\dots E_{1}$)$\cdot A=I_{n}$
- Every elementary matrix is invertible
![[Pasted image 20250205080831.png]]
- $A^-1=E_{k}\dots E_{1}$

- Every invertible matrix is a product of elementary matrices
![[Pasted image 20250205080948.png]]
![[Pasted image 20250205081006.png]]

### Examples
- EX 1
![[Pasted image 20250205081038.png]]
![[Pasted image 20250205081045.png]]
- EX 2
![[Pasted image 20250205081113.png]]

- In order to find the elementary matrices that multiply to $A^{-1}$ we must take A into RREF and record the steps in an elementary matrix
- Multiplying them together greatest to least will result in the inverse matrix
- Doing the same but inverting all the elementary matrices will result in A

- There is a similar story about multiplying an elementary matrix E on the right of A (AE instead of EA) AE is applying the corresponding column operations to A

### Determinant
- $A\in M_{nxn}$ ---> $\det(A)\in\mathbb{R}$
- For a 2x2 matrix:
![[Pasted image 20250205081624.png]]
- The points (0,0) (a,b) (c,d) determines a parallelogram in $\mathbb{R}^2$
- The Area = |ad-bc|
- Base = $\sqrt{ a^2+b^2 }$
- height = $\frac{|ad-bc|}{\sqrt{ a^2+b^2 }}$
![[Pasted image 20250205081638.png]]
- Using this rule we can determine if the determinant is positive or negative area
![[Pasted image 20250205081923.png]]
#### Simple Properties
![[Pasted image 20250205082023.png]]


