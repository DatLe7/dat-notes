### Date: 01-17-2025
### Instructor: Jiayin Pan


## Notes:

### Basis:
- $V\leq\mathbb{R}^n$ a linear subspace, we say $\beta=\{v_{1},\dots,v_{m}\}$ is a basis
  if $\beta$ is a spanning $\mathbb{R}^n$. then #$\beta$ =n 

*Question:* How to check $S=\{\vec{v_{1}},\dots,\vec{v_{n}}\}$ is a basis of $\mathbb{R}^m$?
First of All, m=n ! Meaning A should be a square matrix.
- S is spanning $\mathbb{R}^n$ <=> LS(A|$\vec{b}$) is consistent for all $\vec{b}\in\mathbb{R}^m$
- S is linearly independent <=> LS(A|$\vec{0}$) has a unique solution $x=\vec{0}$
Thus, $S=\{\vec{v_{1}},\dots,\vec{v_{n}}\}\leq\mathbb{R}^m$. A=($\vec{v}_{1},\dots,\vec{v}_{m}$) a mxm SQUARE matrix.
Then the following are equivalent: 
1. S is spanning $\mathbb{R}^m$
2. S is linearly independent
3. S is basis
4. A is non-singular (i.e. A is row equivalent to the identity matrix)
- Identity matrix is represented as $I_{m}$
![[Pasted image 20250120114339.png]]
![[Pasted image 20250120114901.png]]
![[Pasted image 20250120115025.png]]
![[Pasted image 20250120115808.png]]
![[Pasted image 20250120115836.png]]
![[Pasted image 20250120115900.png]]
![[Pasted image 20250120115909.png]]
- Basically saying that the free vectors make up the vectors in the span of the solution matrix(Null(A))
- And the Col(A) is the pivot columns so adding the two up would give you the dimension that A sits in