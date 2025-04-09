### Date: 04-09-2025
### Instructor: Cedric Westphal


## Notes:
### Truth Tables for Statements
- How would we express this statement: **P or Q is true, and it is not the case that both P and Q are true.**
$(P\lor Q)\land \neg(P\land Q)$ 

- This statement contains the individual statements of $(P\land Q)$ and $(P\lor Q)$, as well as $\neg(P\land Q)$ 
![[Pasted image 20250409154703.png]]
- We can write the individual statements and combine the results with the corresponding logical operator to construct the column of a more complex statement
**Example**
![[Pasted image 20250409155255.png]]

### Logical Equivalence
#### Contrapositive Law
- $P\Rightarrow Q=\neg Q\Rightarrow \neg P$
This is proven by this series of equalities
- Also $\equiv$ means "is equivalent to" or "is identically equal to"
$P\Rightarrow Q\equiv \neg P\lor Q\equiv\neg P\lor \neg(\neg Q)\equiv \neg(\neg Q)\lor \neg P\equiv \neg Q\Rightarrow \neg P$
**Example:**
- P(x): "for some $x\in \mathbb{R}$, $x>3$" and Q(x): "for some $x\in \mathbb{R}:x^2>9$". $P\Rightarrow Q$
- Therefore: $\neg Q\Rightarrow \neg P$
- And indeed: "$x^2\leq9$"$\Rightarrow$"$x\leq3$"

#### Negation and Implication
 Formulas $p\Rightarrow q$ and $\neg q\Rightarrow \neg p$ are logically equivalent
- 2nd version $\neg q\Rightarrow \neg p$ is called "**contrapositive**" of the original
- 3rd version $q\Rightarrow p$ is called "**converse**" of original
- Not logically equivalent to original

- 4th version $\neg p\Rightarrow \neg q$ called "**inverse**" of original
- Not logically equivalent to original
- is logically equivalent to 3rd version

### Language for $P\Rightarrow Q$
1. P is necessary for Q
2. P only if Q
3. When P, then Q
"P if Q" is equivalent to $Q\Rightarrow P$

**Bi-conditional:** $(P\Rightarrow Q)\land(Q\Rightarrow P)\equiv P\Leftrightarrow Q$
- "I if and only if Q" or "Q if and only if P" - if and only if sometimes written as iff
- P is necessary and sufficient for Q (Q is necessary and sufficient for P)
- "If P, then Q and conversely"

#### DeMorgan's Law
1. $\neg(P\land Q)=(\neg P)\lor(\neg Q)$
2. $\neg(P\lor Q)=(\neg P)\land(\neg Q)$

### Properties
![[Pasted image 20250409161611.png]]

### Sets & Logic
Given propositions P and Q, define
A = {x | P is true for x} and B = {x | Q is true for x}

- "$x\in A$" and "$x\in B$" can be written "$x\in A\cap B$"
- $P\land Q$: "$x\in A\cap B$"
- "$x\in A$" or "$x\in B$" can be written as "$x\in A\cup B$"
- $P\lor Q$: "$x\in A\cup B$"

- $\neg(P\land Q)$: "$x\in \overline{A\cap B}$" which means "$x\in \bar{A}\cup \bar{B}$" which can be written as $\neg P\lor \neg Q$

**Example:**
![[Pasted image 20250409162446.png]]
