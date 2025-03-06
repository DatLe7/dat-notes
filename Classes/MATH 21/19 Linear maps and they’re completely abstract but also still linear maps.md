### Date: 02-24-2025
### Instructor: Jiayin Pan


## Notes:
- Having a kernel of 0 implies that the map is injective
### Recall
![[Pasted image 20250226155548.png]]
 - The Kernel is the set of all inputs into the linear map to gives the zero vector as an output
 - The Image is the set of all possible output vectors from applying the linear map to some input vector 
![[Pasted image 20250226155601.png]]
- A linear map is considered a linear isomorphism if it is able to take all inputs from its codomain (i.e. $\mathbb{R}^n$)
![[Pasted image 20250226160233.png]]
- If in a finite dimension we can make any vector in the dimension from a linear combination / combination vector of a basis of the dimension
![[Pasted image 20250226160434.png]]
![[Pasted image 20250226160533.png]]
- If a subspace is isomorphic to another subspace then they are both isomorphic to each other
![[Pasted image 20250226160613.png]]
- Big Circle ig
![[Pasted image 20250226160647.png]]
![[Pasted image 20250226160746.png]]

### Properties
![[Pasted image 20250226160828.png]]
- If the dimension of the input vector is reduced when put through a linear map then it is NOT Injective because all inputs will not map to a unique output
 - Image a matrix that is too wide, it will map a $\mathbb{R}^3$ to $\mathbb{R}^2$ since it is too wide that means it is linearly dependent meaning there are infinitely many solutions to the system involving the map below. This means it cannot be injective because there are infinitely many solutions
 $$
\begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6
\end{bmatrix}
\cdot
\begin{bmatrix}
x_{1} \\
x_{2} \\
x_{3}
\end{bmatrix}
=
\begin{bmatrix}
13 \\
22
\end{bmatrix}
 $$

- If the dimension of the input vector is increased when put through a linear map then it is NOT surjective meaning that it can not map to all vectors in its output dimension
- Image a matrix that is too tall and maps from  $\mathbb{R}^2$ to $\mathbb{R}^3$ since it is too tall we cannot map to all vectors in $\mathbb{R}^3$ as we only have 2 pivot columns and can only map to a plane in the codomain
$$
\begin{bmatrix}
1 & 2 \\
3 & 4 \\
5 & 6
\end{bmatrix}
\cdot
\begin{bmatrix}
x_{1} \\
x_{2} \\
\end{bmatrix}
=
\begin{bmatrix}
13 \\
22 \\
42
\end{bmatrix}
 $$
![[Pasted image 20250226161021.png]]
- Image this with matrices.
- If there are more columns than rows then that means it is linearly dependent so there are now multiple ways to map to the zero vector by definition of being linearly dependent
- If there are more rows than columns than the vectors cannot span the entire codomain as there are not enough pivot columns