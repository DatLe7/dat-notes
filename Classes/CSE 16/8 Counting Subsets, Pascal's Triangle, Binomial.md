### Date: 04-16-2025
### Instructor: Cedric Westphal


## Notes:

### K-Permutations
A k-permutation of an n-element set is a non-repetitive length-k list made from
elements of the set.
- If k > n: cannot be non-repetitive! So 0 such permutations
- The number of k-permutations of an n-element set is denoted P(n,k)
$P(n,k)=\frac{n!}{(n-k)!}$

### Counting Subsets
- In a permutations of k=3, there are permutations that are the same set
- The number being 3!
- So given that information we can deduce the number of subsets to be
$C(n,k)=\frac{n!}{k!(n-k)!}$

**Also**
$C(n,k)=C(n,n-k)$
$\frac{6!}{2!(6-2)!}=\frac{6!}{4!(6-4)!}$

**Also**
$C(n+1,k)=C(n,k)+C(n,k-1)$
- Think of $C(n,k)$ as being k subsets that don't contain {0}
- Think of C(n,k-1) also as being k-1 subsets that don't contain {0} but if we union those subsets with {0} then we have the complement of $C(n,k)$ being all the subsets that do contain {0}

### Pascal's Triangle
![[Pasted image 20250420220813.png]]

### Binomial Theorem
![[Pasted image 20250420220835.png]]
![[Pasted image 20250420220844.png]]

