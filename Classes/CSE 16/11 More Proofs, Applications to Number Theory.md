### Date: 04-23-2025
### Instructor: Cedric Westphal


## Notes:

### Goldbach's Conjecture
Goldbach's conjecture is one of the oldest and best-known unsolved problems in
number theory and all of mathematics.

**Every even natural number greater than 2 is the sum of two prime numbers.**

- The conjecture has been shown to hold for all integers less than 4×10 18 butremains unproven.
- Not proven -> not a theorem. It feels true, but we’re not sure. Someone may come up with a counter-example.
![[Pasted image 20250424163030.png]]

### Intro To Proofs
- Most of the things we want to prove in math and computational science is the form $P\to Q$
**Example:** if x > y, where x and y are positive real numbers, then $x^2>y^2$
We can rewrite this in the proposition form we have been using:

**Example, rebooted:** Define the domain for x and y to be all positive real numbers
- If x > y, then $x^2>y^2$

**Example, reboot 2:** $\forall x\forall y((x>y)\to(x^2>y^2))$
	where the domain of discourse is the positive real numbers

- Even though most mathematical propositions aren’t stated using this universal quantifier lingo, they have this flavor.
----
- So how do we prove a statement of the form $\forall x(P(x)\to Q(x))$
	1. Prove $P(c)\to Q(c)$ for any **arbitrary** c.
	2. Conclude $\forall x(P(x)\to Q(x))$ by **universal generalization**
- we usually do this, but we often do not verbalize Step 2
- There are three main ways that we prove P(c) → Q(c)
	- Direct proof
	- Contrapositive proof
	- Proof by contradiction
---
**Direct Proof:** We want to prove $p\to q$ is true. To do this, we only need to show that when p is true, q must be true as well.

**Direct Proof Strategy:** Assume p is true, proceed through a series of rules of inference/mathematical facts (like the stuff we did last time), and eventually end up with q being true as well.

**Definition:** An integer n is even if it can be written as n=2a for some a. And integer is odd if it can be written as n=2b+a for some b. We call the evenness/oddness of n its **parity**

---
**Example Theorem:** If n is an odd integer, then $n^2$ is also odd
**Proof:** 
1. Assume an integer n is odd
	- n can be written as n=2a+1 for some integer a

2. Then $n^2=(2a+1)^2$
		$=4a^2+4a+1$
		$=2(2a^2+2a)+1$
		$=2m+a$                      where $m=2a^2+2a$ for some integer as well
3. Since $n^2=2m+1$ for some integer m, we know $n^2$ must be odd

This concludes the proof. We typically announce this by writing "QED" or a little box: $\square$

---
**Example Theorem:**