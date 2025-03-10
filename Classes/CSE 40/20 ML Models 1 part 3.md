### Date: 02-28-2025
### Instructor: Alexander Rudnick


## Notes:

### Naive Bayes
![[Pasted image 20250310153925.png]]
![[Pasted image 20250310154102.png]]
- Given that we know it is a certain label
- How likely is this feature to be true or a certain value if we already know it is a certain class (P(evidence | cat))
- Probability of being a label (P(cat))
- Probability of feature being a certain value or true or false (P(evidence))
**Simple idea:**
- Assume all features are independent, given the class (conditionally independent)
- Model the relationship between each feature and the class
- Then use Bayes’ rule to compute the overall class probability 
**Key design decisions:**
- Representing probabilistic relationships for different kinds of features
- Smoothing (using prior probabilities) to avoid overfitting
![[Pasted image 20250310153854.png]]
#### Examples
![[Pasted image 20250310154031.png]]
![[Pasted image 20250310154038.png]]

### Naive Bayes for Digit Recognizer
![[Pasted image 20250310154436.png]]
**Simple version:**
- One feature $f_{ij}$ for each grid position <i,j>
- Possible feature values are on / off, based on whether intensity is more or less than 0.5 in underlying image
- Each input maps to a feature vector, e.g.
![[Pasted image 20250310154616.png]]
- Naive Bayes Model:
![[Pasted image 20250310154536.png]]

![[Pasted image 20250310154708.png]]

### General Naive Bayes
**What do we need in order to use naïve Bayes?**

**Inference**
- Start with a bunch of conditionals, P(Y) and the P(Fi|Y) tables
- Use standard inference to compute P(Y|F1…Fn)
- Nothing new here!
**Estimates of local conditional probability tables** 
- P(Y), the prior over labels
- P(Fi|Y) for each feature (evidence variable)
- These probabilities are collectively called the parameters of the model and denoted by θ
- Up until now, we assumed these appeared by magic, but…
- …they typically come from training data
![[Pasted image 20250310154913.png]]

### Generalization and Overfitting
**Relative frequency parameters will overfit the training data!**
- Just because we never saw a 3 with pixel (15,15) on during training doesn’t mean we won’t see it at test time
- Unlikely that every occurrence of “minute” is 100% spam
- Unlikely that every occurrence of “seriously” is 100% ham
- What about all the words that don’t occur in the training set at all?
- In general, we can’t go around giving unseen events zero probability

**As an extreme case, imagine using the entire email as the only feature**
- Would get the training data perfect (if deterministic labeling)
- Wouldn’t generalize at all
- Just making the bag-of-words assumption gives us some generalization, but isn’t enough


**To generalize better: we need to smooth the estimates**
- We don't ever want to see zero probability values in our naive bayes model that is why we use smoothing

### Smoothing
![[Pasted image 20250310155138.png]]
- If we don't have a lot of data do not put a lot of trust in the probabilities
- If we do have a lot of data put more trust in the probability

### Laplace Smoothing
![[Pasted image 20250310155304.png]]
- Gives plus one occurrence to each event
- This makes the high frequency events a little less probability
- and makes the zero frequency events have a very small probability


