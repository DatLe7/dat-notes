### Date: 01-31-2025
### Instructor: Jiayin Pan


## Notes:

### Solving for the inverse
![[Pasted image 20250202145233.png]]
- Adding the two Solutions would give you $A^{-1}$
*More efficient method*
![[Pasted image 20250202145313.png]]
- To sum up. For an invertible matrix A, to find its inverse we consider $(A|I_{n})$ and then do row operations to convert it to $(I_{n}|B)$
![[Pasted image 20250202145441.png]]

### Properties and Equivalences
- non-singular means RREF=$I_{n}$ and Null(A)=$\vec{0}$
- If we can show that A OR B is singular then AB is singular
- If a matrix is non-singular it also means that it is invertible

*Equivalencies for A being non-singular*
1. RREF of A=$I_{n}$
2. $A\vec{x}=\vec{0}$ has a unique solution $\vec{x}=\vec{0}$ (i.e. Null(A)=$\vec{0}$)
3. The column vectors of A are linearly independent
4. $A\vec{x}=\vec{b}$ has a unique solution $\vec{x}$
5. Col(A)=$\mathbb{R}^n$ (Row(A)=$\mathbb{R}^n$)
6. the column vectors of A form a basis of $\mathbb{R}^n$
7. A is invertible

### Transpose
![[Pasted image 20250202150054.png]]

*Properties of Transpose*
1. $(AB)^T=A^TB^T$
2. $(A^{-1})^T=(A^T)^{-1}$
- Property 2 is assuming A is a square matrix
