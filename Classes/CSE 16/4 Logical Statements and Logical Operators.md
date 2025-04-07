### Date: 04-07-2025
### Instructor: Cedric Westphal


## Notes:
### Logic
**Logic Basics**
• Proposition: Statement that can be either true or false.
• Propositional variable: symbols that represent propositions
• Often use lower-case letters like p, q, r, ... In the book, and here: uppercase P, Q, R
• Simple logical operators connect two propositions:
• p and q, q or r, not p.
• Complex propositions built from repeated use of simple operators

Proposition: a statement that is either true or false.
Open sentence or predicate:
P(x): x is even
True or false depending on x
**Examples**
![[Pasted image 20250407161543.png]]
1. Statement and false
2. Statement and true
3. Statement and true
4. not a statement
5. Statement and true
6. Statement and true
7. Statement and false
8. Statement and false
9. not a statement
10. Statement and true
11. not a statement
12. Statement and true
13. Statement and True

### And, Or, Not: Truth Table
![[Pasted image 20250407162355.png]]

### Exclusive Or, Bi-Conditional, Implies: Truth Tables
![[Pasted image 20250407162436.png]]

### Implies Logical Operator
**What does it mean in logic?**
1. It **doesn't** mean "suggests"
2. It **doesn't** mean "causes"
3. Statements with it must **always** has a truth values.

- The ONLY situation in which implication is false is where the Antecedent (i.e. p) is **true**, but the Consequent (i.e. q) is **false**.
- In ALL other situations, the implication is true

**Example**
- If your pet is a dog, then your pet is a mammal.
p (Antecedent) = If your pet is a dog
q (Consequent) = then your pet is a mammal

1. Suppose your pet is a dog.
- p = true
- q = true
- implication is true
2. Suppose your pet is a cat.
- p = false
- q = true
- implication is still true because that doesn't make the statement that a pet dog is a mammal wrong
3. Suppose your pet is a bird.
- p = false
- q = false
- implication is still true because that doesn't make the statement that a pet dog is a mammal wrong
You cannot find a situation where the Antecedent is true but its Consequent is false so this statement is a true implication
![[Pasted image 20250407163740.png]]

**Example**
Is this implication true of false:
$(\sqrt{4}=2\land \sqrt{ 9 }=4)\implies \sqrt{ 30 }=5$
- This is actually a true implication because the Antecedent is never true so the Consequent does not matter

### Biconditional Logical Operator
$P\Rightarrow Q$ is not $Q\Rightarrow P$

$P\Leftrightarrow Q$ abbreviates (P implies Q) and (Q implies P)
- True when P and Q are both true or when P and Q are both false
![[Pasted image 20250407164845.png]]

### Relation of Operators
![[Pasted image 20250407164859.png]]

