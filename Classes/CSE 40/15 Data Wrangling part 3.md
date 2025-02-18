### Date: 02-14-2025
### Instructor: Alexander Rudnick


## Notes:

### Feature Selection
- To generate the best results from your data, it’s essential to identify which variables are most relevant to your hypothesis or objective.
- You can think of selecting features as eliminating columns in your data.
**Automatic Techniques**
	**Filter-based:** Use a specified metric to filter features. 
	**Wrapper-based:** Treat the selection of a set of features as a search problem. 
	**Embedded:** Use a machine learning algorithm that has a built-in feature selection method.

### Filter-Based Feature Selection
- Pearson Correlation Coefficient
- Chi-Squared
- Lots of others!

### Pearson Correlation
- The **Pearson correlation coefficient** is the most common way of measuring a linear correlation. 
- It is a number between –1 and 1 that measures the strength and direction of the relationship between two variables.
![[Pasted image 20250217181615.png]]

### Chi-Squared Test
- A Chi-Square test of independence can be used to determine if there is an association between two **categorical** variables.  (so we can't use this for continuous variables)
![[Pasted image 20250217181716.png]]

### Feature Construction
- Feature construction enriches data by adding derived features.
- Can involve mapping a feature into a new feature using a function like log, or creating a new feature from multiple features using multiplication or addition.

### Row Compression
- Sometimes it makes sense to reduce the number of rows in your data by merging two or more rows into one.


