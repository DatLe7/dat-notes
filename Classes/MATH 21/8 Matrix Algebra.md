### Date: 01-24-2025
### Instructor: Jiayin Pan


## Notes:

### Dot Product (Matrix * Column Vector)
$$
LHS\;gives\;\; A=\
\begin{vmatrix}
a_{11}\dots a_{1}n \\
\vdots\;\;\;\;\;\;\;\;\;\;\;\vdots \\
a_{m1}\dots a_{mn}
\end{vmatrix}
\;\;\; \vec{X}=
\begin{vmatrix}
x_{1}\\
\vdots \\
x_{n}
\end{vmatrix}
$$
- We can define $A\cdot\vec{x}$ as
$$
A\vec{x}=\
\begin{vmatrix}
a_{11}x_{1}\dots a_{1}nx_{n} \\
\vdots\;\;\;\;\;\;\;\;\;\;\;\vdots \\
a_{m1}x_{1}\dots a_{mn}x_{n}
\end{vmatrix}
$$
- A is a mxn  matrix
- $\vec{x}$ is in $\mathbb{R}^n$ 
- The product $A\vec{x}$ in $\mathbb{R}^m$

- The base of A = height of $\vec{x}$, -> $A\vec{x}\in\mathbb{R}^m$
![[Pasted image 20250124155714.png]]
- The i-term is $A\vec{x}$ comes from i-th of A and $\vec{x}$ $\sum^n_{j=i}a_{ij}x_{j}$
![[Pasted image 20250124160006.png]]
![[Pasted image 20250124160018.png]]
- Identity matrix does not change the variables

### Matrix Algebra Properties
![[Pasted image 20250124160104.png]]
- These properties also apply to:
- The i-term is $A\vec{x}$ comes from i-th of A and $\vec{x}$ $\sum^n_{j=i}a_{ij}x_{j}$
- The i-term of A(x+y) is $\sum^n_{j=i}a_{ij}(x_{j}+y_{j})=\sum^n_{j=i}a_{ij}x_{j}+\sum^n_{j=i}a_{ij}y_{j}$ 
- The i-term of (A+B)x is $\sum^n_{j=i}(a_{ij}+b_{ij})x_{j}=\sum^n_{j=i}a_{ij}x_{j}+\sum^n_{j=i}b_{ij}x_{j}$ 
- The i-term of (cA)x is $\sum^n_{j=i}(ca_{ij})x_{j}=\sum^n_{j=i}a_{ij}(cx_{j})$

![[Pasted image 20250124161028.png]]
![[Pasted image 20250124161141.png]]

### Linear Maps
- A map f: A->B (A,B are sets) is an assignment: for each $a\in A$, we assign a unique b=f(a) in B
- A map T from $\mathbb{R}^n$ to $\mathbb{R}^m$ is called linear if:
1. T(x+y) = Tx + Ty for all $x,y\in\mathbb{R}^n$
2. T(cx) = c(Tx) for all $c\in\mathbb{R}$, $x\in\mathbb{R}^n$
![[Pasted image 20250124162358.png]]
![[Pasted image 20250124162425.png]]
![[Pasted image 20250124162517.png]]
