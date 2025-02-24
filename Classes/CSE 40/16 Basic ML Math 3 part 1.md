### Date: 02-19-2025
### Instructor: Alexander Rudnick


## Notes:

### Why Math Matters
- ML algorithms are built on a foundation of mathematics
- **Statistics and probability**: Represent and reason about uncertainty and likelihood of events
- **Linear algebra**: Model relationships between variables
- **Calculus**: Model change in values over time or in relationship to other variables
- These tools are essential for the basics of machine learning:
	**Linear regression**		Summarize the relationship or “trend” between variables
	**Optimization**			Find the best hypothesis in a space of possibilities
	**Gradient descent**		Iteratively move towards better hypotheses / parameters
- linear algebra
	lets us do linear regression and so on
- multivariate calculus
	lets us do gradient descent (for optimization)

### Linear Algebra
- Linear algebra acts as the systematic basis of the representation for simultaneous linear equations.
- Linear algebra allows us to mathematically model and analyze the relationship between variables (features).

#### Vector Norms
![[Pasted image 20250224131107.png]]

#### Dot Product
- If X and Y are two 1 x n vectors, the dot product of X and Y (also called the scalar product) is a measure of how similar or aligned the vectors are.
![[Pasted image 20250224131136.png]]

#### Vector Addition
$X+Y=\{x_{1}+y_{1},x_{2}+y_{2},\dots,x_{n}+y_{n}\}$

### Matrices
- Matrices are two-dimensional arrays of numbers.
- An n x m matrix has n rows and m columns.

#### Matrix Addition
- To add two matrices, we just add the corresponding entries.
- Matrices can only be added together if they have the same dimensions (for 2D matrices, same # rows and columns).
![[Pasted image 20250224131504.png]]

#### Matrix Multiplication
![[Pasted image 20250224131534.png]]

#### Identity Matrix
- The Identity matrix is denoted by $I_{n}$ where n is the dimension
$$I_{3}=
\begin{bmatrix}
1\; 0\; 0 \\
0\; 1\; 0 \\
0\; 0\; 1
\end{bmatrix}
$$
$A\cdot I_{3}=A$

#### Matrix Transpose
![[Pasted image 20250224131828.png]]


#### Matrix Inversion
![[Pasted image 20250224131847.png]]
![[Pasted image 20250224131908.png]]

### Linear Regression
- Linear regression is a mathematical way to draw a “trend” line through data in a scatter plot. The line summarizes the data, which is useful when making predictions.
- When we see a relationship in a scatterplot, we can use a line to summarize the relationship in the data. 
- We can also use that line to make predictions in the data. 
- This process is called **linear regression.**
 ![[Pasted image 20250224132222.png]]
![[Pasted image 20250224132211.png]]

#### How do we find the line of best fit?
![[Pasted image 20250224132357.png]]

### L1 Loss
![[Pasted image 20250224132428.png]]
### L2 Loss
![[Pasted image 20250224132451.png]]


