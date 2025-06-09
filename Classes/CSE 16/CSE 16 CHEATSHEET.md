### Euclidean Algorithm
![[Pasted image 20250515221604.png]]
### lcm & gcd Relation
$a\cdot b=lcm(a,b)\cdot gcd(a,b)$
### Modular Arithmetic Properties

- $(a+b) \bmod m = ((a \bmod m)+(b \bmod m)) \bmod m$  
- $(a-b) \bmod m = ((a \bmod m)-(b \bmod m)+m) \bmod m$  
- $(a \times b) \bmod m = ((a \bmod m) \times (b \bmod m)) \bmod m$  
- $(a^k) \bmod m = ((a \bmod m)^k) \bmod m$  
- Division: if $a^{-1}$ exists, $a \times a^{-1} \equiv 1 \pmod m$  
- $a \equiv b \pmod m \iff m \mid (a - b)$
### Fermat's Little Theorem
$a^{p-1}\equiv1$   (mod p)   If p is prime and p does not divide a
### Bezout's Identity
For any integers a and b, there exist integers x and y such that:
			$gcd(a,b)=ax+by$
### Extended Euclidean Algorithm
1. Apply Euclidean Algorithm to get gcd(a,b)
2. Back substitution with previous equations from Euclidean Algorithm
![[Pasted image 20250515223031.png]]
### Euclid's Lemma
If p is a prime number and p | ab then:
			p | a   or    p | b
If a | bc and gcd(a,b)=1 then:
			a | c
### Combinatorics
**Permutations** = $\frac{n!}{(n-k)!}$
**Combinations** = $\frac{n!}{n!(n-k)!}$
### Properties of Exponents
![[Pasted image 20250515223321.png]]
### Proofs
- **Direct**: Assume $P$, prove $Q$.  
- **Contrapositive**: Prove $\neg Q \Rightarrow \neg P$.  
- **Contradiction**: Assume $P$ and $\neg Q$, reach contradiction.  
- **Base Case**: Verify for starting value(s).  
- **Existence**: Show example exists.  
- **Uniqueness**: Show any two solutions are equal.  
- **Induction**: Prove base; assume true at $k$, prove at $k+1$.  
- **Strong Induction**: Prove base; assume true for all $\leq k$, prove at $k+1$.
### Induction
1. **Base Case:** Prove statement true for initial value $n = n_0$.  
2. **Inductive Step:** Assume true for $n = k$, then prove true for $n = k + 1$.  
3. **Conclusion:** Statement holds for all $n \geq n_0$.
### Strong Induction
1. **Base Case:** Prove true for initial value(s) $n = n_0$.  
2. **Inductive Step:** Assume true for all $n_0 \leq i \leq k$, then prove true for $n = k + 1$.  
3. **Conclusion:** Statement holds for all $n \geq n_0$.
**Note:** Strong induction uses a stronger assumption — assuming the statement holds for *all* values up to $k$ — which can make some proofs easier.
### Proof that $\sqrt{3}$ is Irrational
**Claim:** $\sqrt{3}$ is irrational.  
**Proof by contradiction:**  
Assume $\sqrt{3} = \frac{a}{b}$ with integers $a,b$ in lowest terms.  
Then:  
$$
3 = \frac{a^2}{b^2} \implies a^2 = 3b^2
$$
So, $a^2$ divisible by 3 $\Rightarrow$ $a$ divisible by 3 $\Rightarrow$ $a = 3k$.  
Substitute back:  
$$
(3k)^2 = 3b^2 \implies 9k^2 = 3b^2 \implies b^2 = 3k^2
$$
So, $b^2$ divisible by 3 $\Rightarrow$ $b$ divisible by 3.  
But then $a,b$ share factor 3 — contradicting lowest terms assumption.  
**Conclusion:** $\sqrt{3}$ is irrational.
