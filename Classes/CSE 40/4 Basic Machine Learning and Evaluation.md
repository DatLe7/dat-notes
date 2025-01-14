### Date: 01-13-2025
### Instructor: Alexander Rudnick


## Notes:

### Preface
A typical supervised machine learning algorithm finds a mathematical formula, which, when applied to a collection of inputs (called “training data”), produces the desired outputs. This mathematical formula also generates the correct outputs for most other inputs (distinct from the training data) on the condition that those inputs come from the same or a similar statistical distribution as the one the training data was drawn from.

### Types Of Supervised ML
- Classification: output one of a set of discrete labels.  eg, yes/no, cat/hamster/iguana.
- Regression: output a continuous number.   eg, number between (-inf,+inf), (0,+inf), (0.0,1.0).
- Ranking: Output a ranking, either ordinal (0.0,1.0) or pairwise.

### ML In Practice Workflow
![[Pasted image 20250113200951.png]]

### Optimization Based Supervised Learning Framework
![[Pasted image 20250113201042.png]]
- Classification Inputs: Instances & Labels
### Inputs
#### Instances
- All machine learning algorithms take data as input.
- Most commonly, this data is input as feature vectors.
- But other representations are possible: images, graphs, text, and more.
- Often, we turn whatever we're given into a feature vector before doing the actual ML part -- this is its own art & science!

#### Feature Vector
- A feature vector is simply a vector (represented as an array) of features describing each example.   
For example: salary & education, debt, demographics.
Notation:
1) x is input vector; $x_{i}$ is the ith feature
2) $x_{i}$ is input vector; $x_{ij}$ is the jth feature of the ith input vector

#### Labels
- A label is the correct classification (desired output) associated with a particular input feature vector.
Notation:
1) x is input vector; y is output label
2) $x_{i}$ is input vector; $y_{i}$ is output label
In real-world machine learning problems, a challenge is often where/how to get these correct labels. There is typically a cost associated with getting labeled data.  In addition, in many cases, one has to deal with noisy labels.

### Outputs: Hypotheses
- A tentative explanation for an observation, phenomenon, or scientific problem that can be tested by further investigation.
- In machine learning, we will use the term hypothesis in a couple of different ways.
- The simplest use is as the name for the mathematical function that we learn from data – that function is our hypothesis.

- The hypothesis, h, is a function that maps input feature vectors x to output (predicted) labels y’:
	h: x → y’   or
	h(x) = y’
- Notation:
1)  h(x) is the hypothesis function.
2)  H is the hypothesis space (i.e., the set of all hypothesis functions being considered).
- Our goal is to find good hypotheses!

### Optimization Framework
![[Pasted image 20250113201613.png]]
- Explained: the sigma function finds the hypotheses' average loss over all its predictions
- argmin finds the hypothesis with the least average loss
- hypothesis is an input

#### Loss Function
- The loss function measures the difference between the output of the hypothesis h(x) and the desired output y, for a single observation (x,y).
- You can think of it as measuring the error in the hypothesis.













