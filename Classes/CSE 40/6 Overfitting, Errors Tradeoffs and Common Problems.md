### Date: 01-17-2025
### Instructor: Alexander Rudnick



## Notes:

### Terms
- Model: This is the generic term used for the hypothesis, or function, that is learned.
- Parameters:  The model typically has some parameters, often weights or coefficients, that need to be estimated from the data.
- A "trained" model is a mathematical function or algorithm that maps new inputs to outputs. (we're doing inductive reasoning here)

### Overfitting
- You might think that using a more complex model allows you to recognize more complex relationships and thus should be used often.
- There is an important trade-off: As your model complexity increases, your lowest possible training set error decreases as you would expect.
- However at the same time, the difference between estimated test set error and true error may become larger!
- This phenomenon is called overfitting the data. This means your model is complex enough to simply memorize the data rather than learn from it. 
*Basically the more complex your model gets the better it will do on the training set but the same might not be for the test set as the model is getting complex enough to just memorize the training data and not generalize. This is called overfitting*
![[Pasted image 20250123091219.png]]
![[Pasted image 20250123091230.png]]
![[Pasted image 20250123091242.png]]

### Binary Classification
- A binary classify can only output 1/0, true/false
- A Binary classifier has for possible outcomes for its output
![[Pasted image 20250123091359.png]]
![[Pasted image 20250123091520.png]]
- The matrix on the bottom is called a confusion matrix and can be used to help understand where errors are being made

### Quantities Derived from Confusion Matrix Entries
![[Pasted image 20250123091715.png]]
- Accuracy: How often were you correct?
- Precision: If you said it was a positive case, were you right?
- Recall: out of all the positive cases, how many did you find

### Threshold
![[Pasted image 20250123091844.png]]
- The threshold value could be considered a parameter for the model
![[Pasted image 20250123091917.png]]
#### Approaches
- Choosing optimal threshold
- Draw a graph that captures the tradeoff for different choices of t
- Summarize the graph into a single number that captures how good the model is at all different thresholds

*Draw a graph that captures the tradeoff for different choices of t*
![[Pasted image 20250123092026.png]]
- Shows the relationship between true positive and false positive rate at different threshold values

*Summarize the graph into a single number that captures how good the model is at all different thresholds*
![[Pasted image 20250123092148.png]]
![[Pasted image 20250123092227.png]]

### Common Problems
- Alignment problem
- Plausibility problem

#### Alignment Problem
- It is very important that your formulation of the supervised machine learning problem matches what you really want to have happen in the real world.
- Over and over again, mistakes are made in this regard!
- This is something to keep an eye out for!
![[Pasted image 20250123092532.png]]
- Maximizing Click Through Rate led to rampant clickbait which was not the desired goal
- This means that that label was not good

#### Plausibility Problem
![[Pasted image 20250123092744.png]]
![[Pasted image 20250123092753.png]]
- The first example would not pass the plausibility test because there is no plausible correlation between someone's face and how likely they would be a criminal 