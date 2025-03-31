### Date: 03-5-2025
### Instructor: Alexander Rudnick


## Notes:

### Decision Tree Learning
![[Pasted image 20250311134449.png]]

### Choosing a Attribute
![[Pasted image 20250311134512.png]]
- Yes because it splits them into groups that are mostly homogenous

**The best feature for splitting:**
- The most informative attribute.
- Select the attribute that is most informative about the labels.

**How to measure information?**
- Use **information theory!**

### Information Theory

#### Entropy
**In information theory, entropy measures the uncertainty associated with a random variable.**  
- It quantifies, using expected value, the information contained in a message in bits. 
- Equivalently, it is a measure of the average information content associated with knowing the value of  a random variable.
- Other interpretations: How many bits does it take to encode Y? How many binary questions would be needed to guess the value of Y?
**Definition:**
![[Pasted image 20250311134808.png]]
**Examples:**
- Fair coin: p(heads) = 0.5
	- (.5log.5 + .5log.5 )= 1
- Biased coin: p(heads) = 0.99
	- (.99log.99 + .01log.01 ) = 0.08

#### Information Gain
- To quantify the predictiveness of an attribute X for Y, we consider the conditional entropy, or the expected number of bits needed to encode Y or questions needed to guess Y, **knowing** X. 
![[Pasted image 20250311140020.png]]
- To measure the **reduction in entropy** of Y from knowing X, we use **information gain (IG)**:
![[Pasted image 20250311140045.png]]
- Information gain is how much entropy we got rid of after the split
#### Selecting the best Feature/Attribute
**The best feature for splitting:**
- The most informative feature…
- …in other words, the feature with the highest information gain.
![[Pasted image 20250311140305.png]]
- Splitting by types did not change the entropy at all
- That is why information gain is 0
- Splitting by Patrons make two groups with zero entropy (homogenous types) which lowered the entropy
- that is why there is information gain for splitting by patrons

#### How Big Should the Tree Be? Tradeoff!
**Complete trees…**
- can overfit badly
- have lots of variance
**0 depth trees (always return most likely label) have no variance.**
- Totally biased towards majority label
**A good tree balances between these two.**
- How do we learn good trees...?

### Pruning: New Base Case
- Stop when too few examples
- Stop when max depth reached
- Stop when my classification error is not much more than average of my children
- $Χ^2$ pruning – stop when remainder is no more likely than chance

#### Decision Tree Learning Extensions
- Many other possible split criteria besides information gain – e.g., Gini impurity
- Multi-value attributes: Use gain ratios
- Real-valued data: Use split points
- Noisy data and overfitting: Use pruning
- Missing attributes

### Random Forests
- Random Forest is a tree-based machine learning algorithm that leverages the power of multiple decision trees for making decisions. As the name suggests, it is a “forest” of trees.
- Why do we call it a “random” forest? It is a forest of randomly created decision trees. Each node in the decision tree works on a random subset of features and data to calculate the output. The random forest then combines the output of individual decision trees to generate the final output.
- Very popular approach, often achieves very good performance
![[Pasted image 20250311141229.png]]
#### Decision Tree and Random Forest Properties
**What are some advantages of Decision Trees and Random Forests?**
- Can be used for both classification and regression tasks.
- Work well with both categorical and numerical data.
- No scaling or transformation of variables is usually necessary.
**What are some advantages of Random Forests?**
- Random Forests implicitly perform feature selection and generate uncorrelated decision trees.  This makes them a great model to use when you have a large number of features.
- Random Forests generally provide high accuracy.
- They balance complexity and variance well.
**What are some disadvantages?**
- Random Forests are not easily interpretable. 
- Random Forests can be computationally intensive for large datasets.
- Random forest is like a black box algorithm – you have very little control over what the model does.

### Decision Tree Summary
**Pro: Powerful non-linear model**
**Pro: Intuitive/interpretable model**
**Con: Decision trees have high variance: they are sensitive to small changes in the data.**  
- A small change to data can result in a very different-looking model. (This is considered a bad thing; in an advanced class you’ll study more about the theory of “robustness”).
- Random Forests are one way of overcoming the high variance of decision trees.

### Neural Networks
**Simple idea:**
- Embed lots of perceptron-like nodes in a more complex networks.
- Use backpropagation feedback to learn parameters; use forward propagation to make predictions.
- Allows us to learn nonlinear functions.
**Key design decisions:**
- How many hidden layers? How many nodes in each layer?
- What parameters to use at each node:
- How to backpropagate predictive error? Using what training regimen? (typically using multiple passes over the data, called epochs)

#### Terminology
- Neural networks are made up of **nodes** or **units**, connected by **links**.
- Each **link** has an associated **weight** and **activation level**.
- Each node has an **input function** (typically summing over weighted inputs), an **activation function**, and an **output**.
![[Pasted image 20250311155246.png]]![[Pasted image 20250311155308.png]]
