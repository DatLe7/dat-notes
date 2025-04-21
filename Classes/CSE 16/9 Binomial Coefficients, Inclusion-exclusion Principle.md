### Date: 04-18-2025
### Instructor: Cedric Westphal


## Notes:
### Powersets for S={a,b,c,d,e,f}
- X = {b,d,f} is a subset of S. Y = {a,b,e,f} is another one. ∅ or S as well.
- Consider the vector (0,1,0,1,0,1) such that the element in n-th position in S is included if the corresponding vector coordinate is 1 (and not included if it is 0).
- X corresponds to (0,1,0,1,0,1). Y corresponds to (1,1,0,0,1,1). ∅ to (0,0,0,0,0) and S to (1,1,1,1,1).
- Every subset of S can be described by one and exactly one such vector.
- Therefore |𝒫(S)| = # of vectors of length |S| containing only 0s and 1s

So $\mathscr{P}(S)=2^{|S|}$
Also $\sum^n_{k=0}C(n,l)=2^n$

### Multinomial Theorem
How many ways to pick 2 hands of 5 cards from a deck of 52 cards.

**Method 1**: pick one 1 hand of 5 cards from the deck; for each of these hands you
can then pick a hand of 5 cards out of the remaining 47 cards.
$C(52,5)\cdot C(47,5)$

**Method 2**: pick 10 cards out of 52 cards, then pick 5 cards out of the 10 for one
hand, and 5 for the others
$C(52,10) \cdot C(10,5)$

![[Pasted image 20250420221710.png]]
