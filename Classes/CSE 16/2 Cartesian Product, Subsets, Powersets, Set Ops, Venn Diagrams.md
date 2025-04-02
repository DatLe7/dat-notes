### Date: 04-02-2025
### Instructor: Cedric Westphal


## Notes:

### Cartesian Product
Given two sets A and B, we can multiply them to produce a new set denoted by $A\cdot B$. This operation is called the cartesian product.
**Definition:** A **ordered pair** is a list (x,y) of two elements x and y
- Order matter so $(2,4)\neq(4,2)$
**Definition:** The **Cartesian product** of two sets A and B is another set, denoted by $A\cdot B$ and defined as $A\cdot B=\{ (a,b)|a\in A,b\in B \}$ 
![[Pasted image 20250402140429.png]]
**Property:** $|A\cdot B|=|A|\cdot|B|$
#### Examples
Let A be the set of dice rolls with a cardinality of 6. The $|A\cdot A|=|A|\cdot|A|=6\cdot6=36$
![[Pasted image 20250402140603.png]]
Cartesian product of two sets of numbers can be represented in a 2d graph
![[Pasted image 20250402140731.png]]

**Remark:** Be mindful of parentheses. There is a slight difference between R×(N×Z) and R×N×Z. The first is a Cartesian product of two sets; its elements are ordered pairs (x,(y, z)). The second is a Cartesian product of three sets; its elements are ordered triples (x, y, z).

#### Cartesian Power
The cartesian power of $A^n$ can be represented by
$A^n=A\cdot A\cdot A\cdot A\cdot\;\dots\;\cdot A=\{ (x_{1},x_{2},x_{3},\dots,x_{n}|x_{1},x_{2},x_{3},\dots,x_{n}\in A) \}$
- We can also visualize $\mathbb{R}^2$ as a plane and $\mathbb{R}^3$ as a 3d space

### Subsets
If every element of a set A is an element of another set B, then we say that A is a subset of B.
i.e. $A=\{ 0,2,4 \}$ and $B=\{ 0,1,2,3,4 \}$ then we say A is a subset of B or $A\subset B$ 
**Notation:** $A\subset B$ means A is a subset of B. $A\not\subset B$ means A is not a subset of B meaning there is an element in A that does not exist in B.
**Remark:** The empty set is a subset of all sets so $\emptyset \subset A$ for A any set A. 
**Remark:** A set can also be a subset of itself so $A\subset A$.
- We can represent all possible subsets of a set $B=\{ a,b,c \}$ with a tree
![[Pasted image 20250402143055.png]]
We can consider each subset as a 3 bit map. Where if the element is present then its associated bit will be a 1 else it will be a 0.
**Remark:** If a finite set has n elements, then it has $2^n$ subsets.

### Power Sets
Given a set, you can form a new set with the power set operator.
**Definition:** If a is a set, the **power set** of A is another set denoted by $\mathscr{P}(A)$ and is defined as the set of all subsets of A. $\mathscr{P}(A)=\{ X|X\subset A \}$
**Remark:** From the previous binary map/tree example we can clearly see that $|\mathscr{P}(A)|=2^{|A|}$

### Union, Intersection, Difference
In addition to the operation of cartesian product, sets also have 3 other operation know as union, intersection and difference
**Definitions:**
- The **union** of A and B is the set defined by $A\cup B=\{ x|x\in A \;or\;x\in B \}$
- The **intersection** of A and B is the set defined by $A\cap B=\{ x|x\in A \;and\;x\in B \}$
- The **difference** of A and B is the set defined by $A- B=\{ x|x\in A \;and\;x\notin B \}$

#### Interval
Intervals are denoted by $[a,b]$ and is defined by $[a,b]=\{ x\in \mathbb{R}|a\leq x\leq b \}$
- brackets mean that the end of the interval is included so it would be $\leq$ on the set
- parenthesis means that the end of the interval is not included so it would be $<$ on the set

### Complement
In this context, anything not in P should still be in N. This larger set N is called the **universal** **set** or **universe** for P.
**Definition:** Let A be a set with a universal set U. The **complement** of A is denoted by $\bar{A}$ and is defined as $\bar{A}=U-A$

### Venn Diagrams
![[Pasted image 20250402145327.png]]
![[Pasted image 20250402145332.png]]
![[Pasted image 20250402145306.png]]
![[Pasted image 20250402145314.png]]
**Important Points**
- If an expression involving sets uses only ∪, then parentheses are optional.
- If an expression involving sets uses only ∩, then parentheses are optional.
- If an expression uses both ∪ and ∩, then parentheses are **essential**.