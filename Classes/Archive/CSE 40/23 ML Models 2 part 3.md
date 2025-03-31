### Date: 03-7-2025
### Instructor: Alexander Rudnick


## Notes:

### Model Complexity
**Intuition:**
- Simple models have fewer parameters and have less complex decision boundaries…
- …but may not be able to fit the data as well in **practice**.
**Models, from Least Complex to Most Complex**
- average/mode
- linear models
- naive Bayes
- decision trees
- nearest neighbor
- neural networks

### Overfitting
- You might think that using a more complex model allows you to recognize more complex relationships and thus should be used often.
- There is an important trade-off: As your model complexity increases, your lowest possible training set error decreases, as you would expect.  
- However, at the same time, the difference between this and estimated test set error/true error may become larger. 
- This phenomenon is called **overfitting** the data. It occurs when our model is complex enough to simply memorize the data rather than learn or generalize from it. 
**Definition:**
Overfitting: The phenomenon when the relationship learned by the model is too specific to the data in the sample, causing the model not to generalize well to the true population. This often occurs when the model is too complex or when the data in the sample is bad.
![[Pasted image 20250311155509.png]]
![[Pasted image 20250311155520.png]]
![[Pasted image 20250311155539.png]]

### Setting Hyperparameters
**Now we have two kinds of unknowns**
- **Parameters**: the weights in the model, the decision tree splits, etc.
- **Hyperparameters**, like the amount of regularization to do: k, etc.

**How to learn?**
- Learn parameters from training data.
- Tune hyperparameters on different data.
- For each value of the hyperparameters, train and test on the held-out data.
- Choose the best value and do a final test on the test data.

- We have training data to train the parameters
- We have development/held out data in order to tune the parameters
- We have test data to evaluate our model

### K-Fold Cross Validation
**Rather than choosing random splits with replacement…**

**Proper k-fold cross validation works as follows:**
- Split the data into k equally sized splits.
- For each split, use it as test data, while using the other k-1 splits as training data.
- Compute the average and standard deviation of your performance metric (accuracy, F1, etc.).
![[Pasted image 20250311155853.png]]
![[Pasted image 20250311155910.png]]

### Statistical Hypothesis Testing
- Formal method for evaluating how likely an empirical hypothesis is to be true.
- There are a bunch of different statistical tests, each suited to different settings.
- In the case of comparing multiple machine learning algorithms (MLA) using k-fold cross validation on the SAME splits, the most common method used is called a paired t-test.

### Box Plot
- One useful way to visualize the mean and standard deviation of multiple algorithms is using a box and whisker plot.
- It shows the minimum, first quartile, median, third quartile, and maximum of the distribution.
![[Pasted image 20250311160023.png]]
![[Pasted image 20250311160037.png]]