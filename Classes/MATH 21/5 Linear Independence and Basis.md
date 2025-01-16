### Date: 01-15-2025
### Instructor: Jiayin Pan


## Notes:

### Linear Independence
- $S=\{\vec{v}_{1},\dots,\vec{v}_{n}\}\leq\mathbb{R}^m$ . S is linearly independent if $c_{1}\vec{v}_{1},\dots,c_{n}\vec{v}_{n}=\vec{0}$ implies $c_{1}=..=c_{n}=0$, otherwise S is linearly dependent
- This is basically saying that if the ONLY way to create a zero vector is to have all constants be zero then it is linearly independent. So if there is a way to make the zero vector without having all constants be zero then it is linearly dependent.
*Example:* 
![[Pasted image 20250116091055.png]]
![[Pasted image 20250116091155.png]]
![[Pasted image 20250116091209.png]]
- Adding that fourth vector allows for the set to have a non-trivial(where NOT all the constants are zero) solution to $\{A|\vec{0}\}$ making it linearly dependent
- Also if the solution is infinitely many solutions then the set of vectors is linearly dependent
- If it has a unique solutions then linearly independent
#### Approach To Solving
![[Pasted image 20250116091603.png]]
- Basically you must put the set of vectors into a augmented matrix and solve for the zero vector. If it ends up being a unique solution where the solution is the zero vector then S is linearly independent
![[Pasted image 20250116092520.png]]
- This means that if S is linearly dependent there will exist some vector in the set that can be expressed as a linear combination of the other vectors
-  $\vec{v}_{j}\in span(S-\{\vec{v}_{j}\})$ This means that $\vec{v}_{j}$ can be created as a linear combination even after it is removed from the set meaning that it is a linearly dependent vector
![[Pasted image 20250116092826.png]]
- Basically if a vector is not in the span(S) then you can add it to S and it will still be linearly independent. This is because is $\vec{u}$ not being in the span(S) means that is cannot be created through a linear combination of S
![[Pasted image 20250116093011.png]]
- N=Amount of Vectors
- M=The dimension of the vectors (i.e. (1,2,5) is third dimension so m=3)
1. If the Span(S) can create vectors for all vectors in $\mathbb{R}^m$ then $n\geq m$ because the span(S) is determined by the amount of pivot columns
2. If S is linearly independent then $n\leq m$ because there can only be m amount of pivot columns, so anymore vectors afterwards can always be expressed as a linear combination

### Basis
![[Pasted image 20250116093803.png]]
![[Pasted image 20250116093811.png]]
*Basis:* In linear algebra, a "basis" is a set of linearly independent vectors within a vector space that can be used to represent any other vector in that space by combining them using scalar multiplication; essentially, it's the minimum set of vectors needed to "span" the entire vector space, where each vector in the set can be uniquely combined to create any other vector within the space.

- Essentially, it's the minimum set of vectors needed to "span" the entire vector space, where each vector in the set can be uniquely combined to create any other vector within the space.

