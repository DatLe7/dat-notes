### Date: 01-06-2025
### Instructor: Jiayin Pan


## Notes:
### Gaussian Elimination
- The goal of Gaussian Elimination is to eliminate as many variables as possible to change your matrix/system of linear equation into Row Echelon Form or Reduced Row Echelon Form
- There are three operations that you are allowed to do in Gaussian Elimination
1. Switch i-th and j-th equation
2. Multiply a number c != 0 to i-th equation
3. Replace i-th equation by i-th equation/rows + c * j-th equation
###  Row Echelon Form
![[Pasted image 20250106164657.png]] 
- The leading variables must also have a coefficient of 1
- Ex: Would be in row echelon form because x1 is not in the linear equations of x2 and x3. x2 is also not in the linear equation of x3. It is also in row echelon form as the leading variables have a coefficient of 1$$
\begin{vmatrix}
x_{1}+2x_{2}+5x_{3}\\
x_{2}+3x_{3}\\
x_{3}\\
\end{vmatrix}
$$
Converting system of equations into matrix form
$$
\begin{vmatrix}
1 2 5 \\
0 1 3 \\
0 0 1
\end{vmatrix}
$$
### Row Echelon Form(REF) vs Reduced Row Echelon Form(RREF)
![[Pasted image 20250107155014.png]]
- RREF is Row Echelon Form but all of the leading/pivoting variables must be the only non-zero value
- Pivot columns are columns where the only non zero value is the leading integer
- Pivot columns are the leading variables
- The rest of free variables

![[Pasted image 20250106171059.png]]

### Definitions
- A system of linear equations is consistent, if it has at least on solution
- A system of linear equations is homogenous if bx=0 for all C otherwise inhomogeneous
- In my words, A system of linear equations/augmented matrix is homogenous if the b vector is a zero vector (A|$\vec{0}$)
![[Pasted image 20250108210128.png]]




