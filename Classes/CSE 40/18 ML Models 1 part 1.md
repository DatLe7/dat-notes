### Date: 02-24-2025
### Instructor: Alexander Rudnick


## Notes:

### Decision Boundaries / Hypothesis Spaces
![[Pasted image 20250310145450.png]]

### Search Methods
![[Pasted image 20250310145559.png]]

### Cross Entropy Loss
![[Pasted image 20250310150251.png]]
![[Pasted image 20250310150358.png]]
![[Pasted image 20250310150426.png]]

### Hinge Loss
![[Pasted image 20250310150557.png]]

### Regression vs. Classification
![[Pasted image 20250310150620.png]]

### Sigmoid Function
![[Pasted image 20250310150715.png]]

### Terminology for Linear Classifiers
![[Pasted image 20250310150817.png]]

### Linear Models
![[Pasted image 20250310150833.png]]
- A feature with a high magnitude of weight means that it is very important for predition
- While if the weight of a feature is negative that means that it is negatively correlated

- The goal of learning is to find the best weight vector (i.e., the best parameters 𝜽).
- Generalized linear models all use a weight vector

### Optimization for Linear Classifiers
![[Pasted image 20250310151423.png]]
### Regularizer Term
- Regularizer punished models for being too complex (prefers weights with lower magnitudes closer to zero)
- We can use various distance metrics (also called norms) to measure the effective size of the weight vector / parameters.
![[Pasted image 20250310151706.png]]

### Norm-Based Regularizers
![[Pasted image 20250310151724.png]]

### Gradient Descent
- We take iterative steps to update parameters in the direction of the gradient to get the a local min with respect to the loss function
![[Pasted image 20250310151918.png]]
![[Pasted image 20250310151932.png]]

