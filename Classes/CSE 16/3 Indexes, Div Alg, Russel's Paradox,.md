### Date: 04-04-2025
### Instructor: Cedric Westphal


## Notes:

### Indexed Sets
**Definition:** Generalization of the definition of the union/intersection for multiple sets $A_{1},A_{2},A_{3},A_{n}$ 
 This is denoted by:
 $\cup^n_{i=1}A_{i}=A_{1}\cup A_{2}\cup A_{3}\cup\dots\cup A_{n}=\{ x|x\in A_{i}\;for\;at\;least\;one\;set\;A_{i},\;for\;1\leq i\leq n \}$
 and
 $\cap^n_{i=1}A_{i}=A_{1}\cap A_{2}\cap A_{3}\cap\dots \cap A_{n}=\{ x|x\in A_{i}\;for\;every\;set\;A_{i},\;for\;1\leq i\leq n \}$
 
**Indexing Through Sets**
- We have another way to write this union/intersection of multiple sets
$\cup_{i\in \mathbb{Z}}A_{i}$ where $A_{i}=[i,i+1]$ for $i\in \mathbb{Z}$
This will index through all values in $\mathbb{Z}$
$\cap_{i=1}^3A_{i}=\cap_{i=\{ 1,2,3 \}}A_{i}$

### Number Systems
Sets have some implicit properties -  that are accepted
**Example:** The sets $\mathbb{N},\mathbb{Z},\mathbb{Q},\mathbb{R}$ are closed with respect to addition and multiplication
- This means that if you take two elements from the set and add or multiply them then the resulting sum/product will still belong in the set.
$a\cdot b\in\mathbb{N},\mathbb{Z},\mathbb{Q},\mathbb{R}$ if a and b are in $\mathbb{N},\mathbb{Z},\mathbb{Q},\mathbb{R}$
$a+b\in\mathbb{N},\mathbb{Z},\mathbb{Q},\mathbb{R}$ if a and b are in $\mathbb{N},\mathbb{Z},\mathbb{Q},\mathbb{R}$

- operations +, x are commutative, associative and distributive
- ordering: a ≤ b and b ≤ c implies a ≤ c or that ax ≤ bx if 0 ≤ x or bx ≤ ax o/w

### Well-Ordering Principle
- Another property: every subset in $\mathbb{N}$ has a smallest element
If $A\subseteq \mathbb{N}$ and $A\not=\emptyset$, then there is an element $x_{0}\in A$ that is smaller than other elements of A
- You can start counting 1,2,3,4,... until you reach an element $x_{0}\in A$

Similarly, if $A\subseteq \{ b,B+1,b+2,b+3,\dots \}$ where $b\in \mathbb{Z}$, then A has a smallest element as well

$\mathbb{R}$ does not have this property: (0,1] does not have a smallest element
- This is because you can keep getting infinitely closer to 0
$\mathbb{Q}$ also does not have this property: $A=\left\{  \frac{1}{n}|n\in \mathbb{N}  \right\}$
- This is because the fractions can keep getting smaller $\frac{1}{n+1}\in\mathbb{Q}$

### Division Algorithm
Given Integers a and b with b>0, there exist unique **integers** q and r for which $a=qb+r$ and $0\leq r<b$
**Example:** for a=19 and b=7: $19=2\cdot 7+5$ where q=2 and r=5

### Russell's Paradox
$A=\{ X|X\;is\;a\;set\;and\;X\not\in X \}$
In words, A is the set of all sets that do not include themselves as elements.
Most sets we can think of are in A. The set Z of integers is not an integer
(i.e., Z ∉ Z) and therefore Z ∈ A. Also $\emptyset$∈ A because $\emptyset$ is a set and $\emptyset$∉$\emptyset$.

