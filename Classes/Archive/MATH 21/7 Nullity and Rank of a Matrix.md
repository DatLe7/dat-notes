### Date: 01-22-2025
### Instructor: Jiayin Pan


## Notes:

### Nullity and Rank
*Goal: Given an nxm matrix A find:*
1. A basis for Null(A). dimNull(A) or Nullity(A)
2. A basis for Col(A). dimCol(A) or Rank(A)
- This is three different ways of saying the same thing

- Rank(A) = number of pivot columns
- Nullity(A) = number of free variables

- Col(A) is the pivot columns
- Null(A) is the solution vectors
### How to Solve
![[Pasted image 20250123085101.png]]
- We can put the matrix into RREF and find the solution
- The basis of Null(A) is given by the set of solution vectors to $LS(A|\vec{b})$
- The basis of Col(A) is given by the pivot columns

### Observations
- Rank(A) = # pivots = r
- Nullity(A) = # free variables in $LS(A|\vec{0})$ = n - # pivots = n - r
- Rank(A) + Nullity(A) = r + (n - r) = n
- Adding Rank(A) and Nullity(A)/ Adding the # of pivots and free variables gives you the total amount of vectors in the matrix (amount of vectors in the matrix = n)
### Quick Dat Note
- If a set of vectors has the zero vector in it, then by definition it is linearly dependent
- This is because you can set the zero vector to any constant and the rest to the zero constant and that would give a non-trivial solution to $LS(A|\vec{0})$ making it linearly dependent