### Date: 01-13-2025
### Instructor: Jiayin Pan


## Notes:

### Linear Subspace
- Let V be a subset of $\mathbb{R}^n$. We can say V is a _Linear Subspace_, if V is closed under 2 circumstances:
1. $\vec{u}+\vec{v}\in V\;\;for\:all\:\vec{u},\vec{v}\in V$
2. $c\vec{u}\in V\;\;for\:all\:\vec{u}\in V\;and\;c\in\mathbb{R}$
- 1. Any two vectors that are linear combinations of V/fall in its span must be able to be multiplied together and the product must still fall in the span of V
- 2. Any vector that that is a linear combinations of V/falls in its span must remain in the span of V even after multiplying it by any constants
- The zero vector must also be included for V to be a linear subspace
![[Pasted image 20250113205243.png]]
![[Pasted image 20250113205254.png]]
#### Null(A)
![[Pasted image 20250113205448.png]]
- Null(A) is the linear subspace of all vectors that solve the augmented matrix/system of linear equations
![[Pasted image 20250113205625.png]]
![[Pasted image 20250113213813.png]]
![[Pasted image 20250113213943.png]]
![[Pasted image 20250113214006.png]]
![[Pasted image 20250113214126.png]]
![[Pasted image 20250113214143.png]]
- Null(A) is the subspace of all solutions to the A and that span is represented by the spanning set of S
![[Pasted image 20250113214242.png]]
- In the second example the third vector can be removed and the spanning set would be the same
- This is because that vector is not a linear independent vector while the first two are
- The definition of a linear independent vector is one that cannot be created through linear combinations or scaling off of other vectors in the set
![[Pasted image 20250113214428.png]]
![[Pasted image 20250113214514.png]]
![[Pasted image 20250113214549.png]]
- We can also say that a set is linearly independent if we are unable to create a zero vector off of their linear combinations
- If we are able two that means that it is not linearly independent meaning their are/is vectors/vector that do not add new information and are redundant

### LAB SECTION SNEAK PEAKS
- Free variables are variables that you can pick any value for and get the other values. This is why when their is at least one free variable, then it means infinite solutions because their will be infinity many values for the free variable where you can still get a solution
- ${0_{i}+\dots+0_{n}}=c\;|\;c\neq_{0}$ row results in their being no solution because the statement comes down to 0=5 or 0=3 which is impossible
- The row operation where we add/subtract a row from another does not change the truth of the system of equations because we are adding the same thing to both sides because they equal each other
- Span is determined by the amount of pivot positions/variables
- If you can make a vector with scalar multiplication or linear cementations of other vectors in the set then it is redundant and provides no new information
- linear independent means cannot be made as linear commination of other vectors in set
- COMING UP: linear independence next then basis