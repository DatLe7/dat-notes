### Date: 04-14-2025
### Instructor: Cedric Westphal


## Notes:

### Logical Inference
The rules of inference provide a system in which we can produce new information
(statements) from known information

- $P\Rightarrow Q$. If P is true, then we can infer that Q is true.
- "P implies Q". P is true. Therefore, Q must also be true
- **Modus Ponens** or affirming the antecedent

- $P\Rightarrow Q$. If Q is false, then we can infer that P is false.
- "P implies Q". Q is false. Therefore, P must also be false.
- **Modus Tollens** or denying the consequent

### Combinatorics
#### Sum Principle
- The number of elements in a finite number of disjoint finite sets A, B, ..., N is the sum of their sizes |A| + |B| + ... + |N|.

- Two sets are disjoint if they have no elements in common
- Note: |S| means size of set S, not the absolute value
![[Pasted image 20250414163703.png]]

#### Product Principle
- The number of elements in the Cartesian product of finite number of finite sets A, B, ..., N is the product of their sizes |A| + |B| + ... + |N|.

- Cartesian product of A x B of sets A, B is all ordered pairs (a, b) where 1st element in A and 2nd element in B.
- Cartesian product of A x B x C of sets A, B, C is all ordered triples (a, b, c) where 1st element in A, 2nd element in B and 3rd element in C.
- Cartesian product of of sets A, B, ..., N is all ordered n-tuples where 1st element in A, 2nd element in B, ..., and n-th element in N.

### List
A list is an ordered set of elements.
- (a, b, c, d, e) $\not=$ (b, a, c, d, e)

- Also unlike sets, a list can have repeated entries: (a, a, a, a, a) is a list
- Two list are **equal** if they have exactly the same entries in the exact same positions

### Multiplication Principle 2
Given sets A = {a,b,c}, B = {5,7}, C = {a,x}, how many lists of 3 elements can we  
create where the first elements is drawn from A, the second from B and the last  
from C
- The number of possible lists is: $|A|\cdot|B|\cdot|C|$
![[Pasted image 20250414164347.png]]

### Subtraction Principle
If X is a subset of U, then $\overline{|X|}=|U|-|X|$

If $X\subseteq U$, |U-X|=|U|-|X|

Application: how many lists of length 4 can be made from A,B,C,D,E,F with
repetition allowed contain at least one E?

Number of such lists that contain at least one E is equal to the total number of lists
minus the lists that contains no E, namely 6x6x6x6 - 5x5x5x5 = 1296 - 625 = 671

### Sum Principle Corollary
![[Pasted image 20250414164818.png]]
A = set of t shirts in my wardrobe. B = set of blue items in my wardrobe.  
How many items are t shirts or blue?
- $|A|+|B|-|A\cap B|$
![[Pasted image 20250414164915.png]]
- If we don't subtract $|A\cap B|$ we would account for those elements twice because |A| and |B| both include $|A\cap B|$

### Factorial
![[Pasted image 20250414165034.png]]

### K-Permutations
A k-permutation of an n-element set is a non-repetitive length-k list made from  
elements of the set.

- Number of k permutations? n choices for first possible elements, (n-1) for the second, ....(n-k+1) for the k-th element, so n(n-1)(n-2)...(n-k+1)
- f k > n: cannot be non-repetitive! So 0 such permutations
- The number of k-permutations of an n-element set is denoted P(n,k), and P(n,k) = n(n−1)(n−2)···(n− k +1).
- If 0 ≤ k ≤ n, then P(n,k) = n(n−1)(n−2)···(n− k +1) = n! /(n− k)!

**Example:**
- 2-permutations of {1,2,3,4,5}: 12, 13, 14, 15, 21, 23, 24, 25, 31, 32, 34, 35, 41, 42, 43, 45, 51, 52, 53, 54

### Permutation and Combinations
![[Pasted image 20250414165111.png]]