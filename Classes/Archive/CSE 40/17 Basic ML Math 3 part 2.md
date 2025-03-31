### Date: 02-21-2025
### Instructor: Alexander Rudnick


## Notes:
### Multivariate Calculus
- Calculus is used for measuring the rate of change of a function. A derivative is the rate of change at a given point in a real-valued function.
- The derivative f'(x) of function f(x) for variable x is the rate that the function f(x) changes at the point x.
- It might change a lot (e.g., be very curved), or might change a little (e.g., have a slight curve), or it might not change at all (e.g., be flat or stationary).
- A function is differentiable if we can calculate the derivative at all points of input for the function variables. (Not all functions are differentiable!)
![[Pasted image 20250224142035.png]]
![[Pasted image 20250224142051.png]]

### Partial Derivative
- A partial derivative is a derivative where we hold some variables constant.
**Example:**
![[Pasted image 20250224142127.png]]

### Gradient
- A **gradient** is a derivative of a function that has more than one input variable.

- The gradient is the generalization of the derivative to multivariate functions. It captures the **local slope** of the function, allowing us to predict the effect of taking a small step from a point in any direction.

- Refers to the derivative of a function from the perspective of linear algebra. When linear algebra meets calculus, it is called **vector calculus**.
![[Pasted image 20250224142611.png]]
![[Pasted image 20250224142636.png]]

### Optimization
![[Pasted image 20250224142752.png]]
#### Convex vs Non-Convex Optimization
![[Pasted image 20250224142832.png]]
- Convex(left) only has one local minimum making that the global minimum
- Non-Convex(right) has multiple local minimums making Optimization a little more tricky
![[Pasted image 20250224142951.png]]

### Gradient Descent
- Gradient Descent is an optimization strategy for finding a local minimum of a differentiable function. 
- Within ML, gradient descent is used to find the values of a function's parameters that minimize a loss function (as much as possible).
![[Pasted image 20250224143047.png]]
![[Pasted image 20250224143103.png]]

### Non-Convex Optimization
![[Pasted image 20250224143133.png]]
![[Pasted image 20250224143140.png]]
