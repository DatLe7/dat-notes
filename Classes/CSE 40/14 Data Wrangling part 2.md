### Date: 02-12-2025
### Instructor: Alexander Rudnick


## Notes:

### Outliers
- An **outlier** is a value or point that differs substantially from the rest of the data.
- Choosing outliers use either **domain knowledge** or a **statistical test**

Two statistical indicators are commonly used:
	 Distance from the mean in standard deviations.
	 Distance from the interquartile range by a multiple of the interquartile range.

With Doman Knowledge
	Sometimes, a typical range of values are known

### Normalization
- Rescale the range of values for a given feature into a set range, such as [0, 1] or [-1, 1]
- **Normalization** is a technique applied to change the values of numeric columns in the dataset to use a common scale. This is typically done when the features in your dataset have different ranges.
#### Min-Max Scaling
Min-max scaling is...
x' =   (x - min)  / (max - min)

### Standardization
![[Pasted image 20250217181034.png]]

### Feature Engineering
Sometimes we want to:
	Modify how features are represented - **feature transformation**
	Add features to our data – **feature construction**
	Remove features from our data – **feature selection**

Collectively, these techniques are often referred to as **feature engineering.**

### Feature Transformation
**Feature transformation** refers to a set of methods for transforming existing data into a new representation that will lead to more effective learning
	Text → numeric: 						one-hot encoding
	Numeric → categorical: 				binning (aka discretization)
	Many categories → fewer categories: 	grouping

#### One-hot Encoding
Convert a categorical feature having string labels into K numerical features in such a manner that the value of one out of K (one-of-K) features is 1 and the value of rest (K-1) features is 0

#### Binning / Discretization
Sometimes you want to go the other direction, converting numeric (integer or real-valued data) to categorical.
![[Pasted image 20250217181306.png]]

### Grouping
- Sometimes a categorical (discrete, non-numeric) feature can be very high-dimensional (i.e., have a very large number of different values in a data set)
- The solution is to group similar values together