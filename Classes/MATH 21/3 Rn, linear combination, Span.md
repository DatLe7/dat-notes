### Date: 01-10-2025
### Instructor: Jiayin Pan


## Notes:

### Vector Space and Algebraic Vector Operations
![[Pasted image 20250110221535.png]]
![[Pasted image 20250110221555.png]]

### Linear Combinations
- *Definition*: Given {$\vec{v}_{i},\dots,\vec{v}_{n}$} in $\mathbb{R}^m$, and $c_{1},\dots,c_{n}\in\mathbb{R}$. We say $c_{1}\vec{v}_{1}+\dots+c_{n}\vec{v}_{n}$ is a **linear combination** of {$\vec{v}_{1},\dots,\vec{v}_{n}$}. ($=\sum_{i=1}^nc_{i}\vec{v}_{i}$) 
- *Question*: Given {$\vec{v}_{i},\dots,\vec{v}_{n}$} in $\mathbb{R}^m$, and $\vec{b}\in\mathbb{R}^m$. is $\vec{b}$ a linear combinations of {$\vec{v}_{i},\dots,\vec{v}_{n}$}.
- *Definition*: Let S = {$\vec{v}_{i},\dots,\vec{v}_{n}$}$\leq\mathbb{R}^m$. the set of all linear combinations  
  {$\vec{w}=\sum_{i=1}^nc_{i}\vec{v}_{i}$ | $c_{i}\in\mathbb{R}.\vec{c}=1,n$} is called the span of S. denoted by span(S) or $<S>$
  ![[Pasted image 20250110224226.png]]
  - This is a linear system with an augmented matrix. ($\vec{v}_{1},\dots,\vec{v}_{n}|\vec{b}$). Conversely, for a linear system with augmented matrix (A|$\vec{b}$). (A m x n matrix) We write A as a collection of n many column vectors in $\mathbb{R}^m$ 
    A = ($\vec{A}_{1},\dots,\vec{A}_{n}$), 
    then the linear system:$$
\begin{vmatrix}
a_{11}c_{1}+\dots+a_{1n}c_{n} \\
\vdots \\
a_{1n}c_{1}+\dots+a_{nm}c_{n}
\end{vmatrix}
$$
	can be written as $$
x_{1}
\begin{vmatrix}
a_{11} \\
\vdots \\
a_{1m} \\
\end{vmatrix}
+
\dots
+
x_{n}
\begin{vmatrix}
a_{1n} \\
\vdots \\
a_{nm} \\
\end{vmatrix}
$$
	i.e. $\sum_{i=1}^nx_{i}\vec{A}_{i}=\vec{b}$
### Span
**To sum up, whether $\vec{b}\in\mathbb{R}^m$ is a linear combination of {$\vec{v}_{i},\dots,\vec{v}_{n}$} is equivalent to ask whether the linear system with augmented matrix ($\vec{v}_{i},\dots,\vec{v}_{n}$|$\vec{b}$) is consistent**
*Reminder*: A system of linear equations is consistent, if it has at least on solution
![[Pasted image 20250110230045.png]]
![[Pasted image 20250110230058.png]]
![[Pasted image 20250110230110.png]]
![[Pasted image 20250110230248.png]]
- If an A vector has more rows then columns (m>n) then it is inconsistent has in RREF there will always be a row with all zeros as there can only be n amount of pivot position/columns. That means that we are able to find a $\vec{b}$ where the row of zeros equals a non-zero value making it have no solutions.

- The span of a matrix is determined by how many pivot positions it has so if the matrix is in $\mathbb{R}^4$ space but only has 3 pivot positions then its span is only $\mathbb{R}^3$ 

