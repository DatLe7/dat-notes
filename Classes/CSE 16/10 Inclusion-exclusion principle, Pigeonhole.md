### Date: 04-21-2025
### Instructor: Cedric Westphal


## Notes:
### Combinatorial Proof
$\sum^n_{k}C(n,k)^2=C(2n,n)$

C(2n,n) = choosing n elements out of a list of 2n elements.
Split your 2n list into two lists A and B of combined length n.
$C(n,k)C(n,n-k)=C(n,k)^2$
This is because C(n, k) & C(n, n-k) is the same value
The number of ways to choose k items for set A is C(n, k) 
The number of ways to choose n-k items for set B is C(n, n-k)

So the total number of ways to choose items from A & B is C(n, k)C(n, n-k)=$C(n, k)^2$
If you sum all over all possible values of k then the total number of ways is $\sum^n_{k}C(n, k)^2$

### Inclusion Exclusion Principle
**Claim:** $|A\cup B|=|A|+|B|-|A\cap B|$

- This is because |A| & |B| both include $|A\cap B|$ so you need to subtract it once because it is represented in both |A| & |B|

**Example:**
How many 3-card hands are all diamonds or all face cards?

A = {all diamonds 3-card hands} B = {all face card 3-card hands} We want $|A\cup B|$

$|A\cup B|=|A|+|B|-|A\cap B|$

$|A|=C(13,3)=286$ - There are 13 total diamond cards
$|B|=C(12,3)=220$ - There are 12 total face cards
$|A\cap B|=C(3,3)=1$ - There are 3 total diamond face cards

$|A\cup B|=|A|+|B|-|A\cap B|=286+220-1$

### Pigeonhole Principle
n = # of pigeons
m = # of containers

**Proof**: if there is at most one pigeon in each hole, then we can have at most n  
pigeons, but m > n.  

**Proof**: if there is at most k pigeons in each hole, then we can have at most kn  
pigeons, but we have m > kn pigeons.

**Example:**
Given 6 different random numbers between 0 and 9, two will add up to 9.

Proof: consider the following 5 boxes
![[Pasted image 20250424161341.png]]
- Put the 6 numbers each into the box that is labelled with that number. There are 5
boxes and 6 numbers, so 2 will be in the same box.

In this case n=6 and m=5 so according to the pigeonhole principle k=2 b/c 
m(5) > k(2) * n(6)
So there is at most k(2) pigeons in each container

### Wheel of Fortune
Consider a wheel of fortune with 10 numbers 1 through 10. The numbers are placed around the
wheel in a random order.
**Claim**: there are 3 consecutive numbers on this wheel such that their sum is greater than 17.

Denote the numbers as x1, x2, x3, ... x10. Assure each consecutive triplet is ≤16.
x1 + x2 + x3 ≤16
x2 + x3 + x4 ≤16
x3 + x4 + x5 ≤16
x4 + x5 + x6 ≤16
...
X9 + x10 + x1 ≤16
x10 +x1 + x2 ≤16

Given the assumption that all combinations of triples is less than or equal to 6 that must mean that the value of the sum of all triples must be less than $16\cdot 10$ according to the inequality

The value of the sum of the combinations is denoted by $3\cdot \sum_{i={1,2,3,\dots,10}}i=165$
Since the value of the sum of all combinations is more than 160 that must mean that not all triples are $\leq16$ meaning there must exist a combination of 3 consecutive number whose sum is greater than 17

### Proof Basics
- Definition: precise statement of meaning of term.
- Conjecture: proposed statement with supporting evidence.
- Theorem: statement with a proof.
- Lemma: small statement used to prove some bigger statement.
- Corollary: something that follows directly from related theorem.
- Proof: Argument so convincing that it compels consent
- Direct Proof: Simple proof “template” discussed in Chap 1.

#### Definitions
A **theorem** is a mathematical statement that is true and can be (and has been)  
verified as true.

A **statement** that is true but not as significant is sometimes called a **proposition**. 
A **lemma** is a theorem whose main purpose is to help prove another theorem. 
A **corollary** is a result that is an immediate consequence of a theorem or  
proposition.

**Direct Proof**
$P\Rightarrow Q$
![[Pasted image 20250424162613.png]]

**Definitions**
Statement to specify the meaning of terms
![[Pasted image 20250424162649.png]]
![[Pasted image 20250424162657.png]]

### Axioms or Assumptions
![[Pasted image 20250424162720.png]]
