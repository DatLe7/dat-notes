### Date: 01-08-2025
### Instructor: Jiayin Pan


## Notes:

### Matrix Form of Linear Equations
![[Pasted image 20250108210238.png]]
- System of linear equations can be converted into a matrix where the matrix is m rows by n columns and each of the values are the coefficients of the x unknowns in the system of equations
#### Types of Vectors
![[Pasted image 20250108210428.png]]
- A vector is a n by 1 matrix
- A constant vector consist of constants and NO unknowns
- A unknown vector consists of unknowns/variables and no CONSTANTS
- An augmented matrix consists of the coefficient matrix and a constant vector
- The coefficient matrix is found from the coefficients of the unknowns of your system of linear equations where each column is the coefficients of x1,x2,x3,...,xn

#### Gaussian Elimination
- The operations done to the equations of the system of linear equations can also be done on the rows of a augmented matrix
- $R_{i}$ and $R_{j}$  are rows in the matrix
1. Switch $R_{i}$  and $R_{j}$ equation/rows
2. Multiply a number c != 0 to $R_{i}$  
3. Replace $R_{i}$  equation/rows by $R_{i}$  equation/rows + c * $R_{j}$ equation/rows
![[Pasted image 20250108211846.png]]
![[Pasted image 20250108212050.png]]
- We can convert RREF matrix into vector form
- Reminder: Vectors are n by 1 matrixes
### Reduced Row Echelon Form(RREF)
- A matrix is considered in RREF if:
1. If a row has all zero entries, it should be below the non-zero rows
2. The leading entry of each row in must be 1
3. If we have leading entries in (i,j)-position and (s,t)-position and i < s, then j < t (basically the leading entries must look like it forms a line from top left to bottom left)
4. The leading entries in a row is the only non-zero entry in its column
![[Pasted image 20250108212632.png]]
- Converting from RREF into Vector Form
![[Pasted image 20250108212729.png]]
### Observations Found From RREF
- A matrix is row equivalent to itself in RREF
- To solve a linear system, write it down in augmented matrix (A|B) form. Apply row-operations to get its RREF, then get solution from there
- Pivot columns are the column with a leading entry in RREF
- The rest of the columns are the free variables
#### Observations about solutions From RREF
- If a row in RREF is like (0 . . . 0| b!=0), then no solutions
*Otherwise*
- If there is a column that is not pivot, then we have a free variable, then there are infinitely many solutions
- If every column is pivot, then there is a unique solution
It looks like this
![[Pasted image 20250108213632.png]]

### Observations Found From the Shape of the Matrix
**Reminder: A system of linear equations is homogenous if bx=0 for all C otherwise inhomogeneous
- If a homogeneous system (A|$\vec{0}$) has # variables > # equations
  A is a m x n matrix where m > n
  ![[Pasted image 20250108214608.png]]
  In its RREF, there must be at least on column that is not pivot, then at least on free variable, hence infinitely many solutions

- Let A be a n x n matrix(square matrix). We say that A is *non-singular*, if its RREF is
  ![[Pasted image 20250108214756.png]]
  In this case, a linear system (A|$\vec{0}$) has a unique solution $\vec{x}=\vec{0}$
  If a linear system (A|$\vec{0}$) then in RREF, all columns are pivot hence:
  ![[Pasted image 20250108215000.png]]

- ![[Pasted image 20250108215050.png]]

  
  

