### Date: 02-26-2025
### Instructor: Alexander Rudnick


## Notes:

### Perceptrons
- Inputs are **feature values**
- Each feature has a **weight**
- Sum is the **activation**
- Add **bias term**, feature that is always 1
![[Pasted image 20250310152423.png]]
In the space of feature vectors
- Examples are points
- Any weight vector is a hyperplane
- One side corresponds to Y=+1
- Other corresponds to Y=-1
![[Pasted image 20250310152707.png]]
- If our model predicts wrong then we learn the model by adding the feature vector multiplied by the true label
- This is different from logistical regression as in logistical regression it learns by doing gradient descent

### Properties of Perceptron Training Algorithm
**Online**
- We look at one example at a time, and update the model as soon as we make an error.
- As opposed to batch algorithms that update parameters after seeing the entire training set.
**Error-driven**
- We only update parameters/model if we make an error.
![[Pasted image 20250310153109.png]]
### Properties of Perceptrons
![[Pasted image 20250310153213.png]]
#### Implications
**Sensitivity to noise**
- if the data is not linearly separable due to noise, no guarantee of convergence or accuracy.
**Linear separability in practice** 
- Data may be linearly separable in practice.
- Especially when number of features >> number of examples.
**Risk of overfitting mitigated by**
- Early stopping.
- Averaging.

### Single Perceptron vs Logistic Regression
**first off, what's the same?**
- linear models with a weight vector based on dot product
- they can learn the same kind of decision surface

**what's different?**
- the training behavior: we train logistic regression with gradient descent
- logistic regression has a loss function and it will just find the surface that minimizes the loss

- Linear Models can only represent linear decision surfaces
- If we want to represent nonlinear decision surfaces we need something other than a linear model
- Something like multi-layer perceptron models or MLP
- Also called feed-forward neural networks




