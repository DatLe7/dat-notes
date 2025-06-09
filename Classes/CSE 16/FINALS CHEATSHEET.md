**Cartesian Product:** A × B = {(a, b) | a ∈ A, b ∈ B}
**Powerset:** If A has n elements, then |P(A)| = 2ⁿ
![[Pasted image 20250608214859.png]]
**Binomial Theorem:** (a + b)ⁿ = Σ C(n, k) · aⁿ⁻ᵏ · bᵏ
![[Pasted image 20250608215147.png]]
**Inclusion-Exclusion Principle:** |A ∪ B| = |A| + |B| - |A ∩ B|
**Relation**
1. $R$ is reflexive $\iff$ for all $x$ in $A$, $(x, x) \in R$
2. $R$ is symmetric $\iff$ for all $x$ and $y$ in $A$, if $(x, y) \in R$ then $(y, x) \in R$
3. $R$ is transitive $\iff$ for all $x$, $y$ and $z$ in $A$, if $(x, y) \in R$ and $(y, z) \in R$ then $(x, z) \in R$
An **equivalence relation** is a special kind of relation that satisfies **all three** properties
##### 🔢 Function Properties
Let $f: A \to B$ be a function.
1. $f$ is **injective** $\iff$ for all $x_1, x_2 \in A$, if $f(x_1) = f(x_2)$ then $x_1 = x_2$
2. $f$ is **surjective** $\iff$ for all $y \in B$, there exists $x \in A$ such that $f(x) = y$
3. $f$ is **bijective** $\iff$ $f$ is both injective and surjective
- **Injective** = one-to-one → different inputs map to different outputs.
- **Surjective** = onto → every element in $B$ is hit by some element from $A$.
- **Bijective** = perfect pairing → every $y \in B$ is hit **once** by exactly one $x \in A$.
##### 🕊️ Pigeonhole Principle
**Basic Form:**  
If $n + 1$ pigeons go into $n$ pigeonholes, at least one hole has $\ge 2$ pigeons.
**Formal:**  
If $f: A \to B$ and $|A| > |B|$, then $f$ is *not* injective.
**Fermat's Little Theorem:** $a^{p-1}\equiv1$   (mod p)   If p is prime and p does not divide a
**lcm & gcd Relation** $a\cdot b=lcm(a,b)\cdot gcd(a,b)$
**Bezout's Identity:** $gcd(a,b)=ax+by$
##### Euclid's Lemma
If p is a prime number and p | ab then:
			p | a   or    p | b
If a | bc and gcd(a,b)=1 then:
			a | c
##### Basic Probability
![[Pasted image 20250609000522.png]]
##### Bayes' Theorem
![[Pasted image 20250609000602.png]]
**Method 1:**  
Let's look at the following string: _ S _ S _ S _ S _ S _ S _ S _ S _ . This is all the 8 Students lined up with the possible spaces for the Professors. There are 9 open spots (1 front of line + 7 between the 8 Ss + 1back of line). So we need to choose 5 spots to create a string such as SSSPSPSPSPSSP (where I chose five spots, namely 4,5,6,7,9 among the 9 spots I could choose from). If I chose the first 5 spots, I would get PSPSPSPSPSSSS, if I chose the 5 last I would get SSSSPSPSPSPSP...) In any case, there are C(9,5) ways to choose the spots for the Professors in this line.