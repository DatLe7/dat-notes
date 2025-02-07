### Date: 01-31-2025
### Instructor: Alexander Rudnick


## Notes:

### Independence and Dependence
In probability, we say two events are independent if knowing whether one event occurred doesn't change the probability of the other event.

Knowing about event A gives us no additional information about event B.
#### Examples
![[Pasted image 20250202152037.png]]
![[Pasted image 20250202152045.png]]
### Independence and Joint Distribution
![[Pasted image 20250202152212.png]]
*Checking for Independence Method 1*
![[Pasted image 20250202152244.png]]
*Checking for Independence Method 2*
![[Pasted image 20250202152337.png]]

### Why are conditional probabilities & independence especially important in machine learning?
![[Pasted image 20250202152432.png]]

![[Pasted image 20250202152527.png]]
- If we have a 10x10 table if we know that the variables are independent instead of having to sore 100 values we can just store 20
- Scaling this up this would save a lot in storage
![[Pasted image 20250202152624.png]]
![[Pasted image 20250202152704.png]]
![[Pasted image 20250202152721.png]]

### Conditional Independence and Dependence
![[Pasted image 20250202153210.png]]
![[Pasted image 20250202153007.png]]
### Top Graph:
- This is a **collider** structure, where two arrows converge into the same node (Quiz).
- **Conditional Independence:**
    - **Unconditionally:** _Study_ and _Sleep_ are **independent** because there’s no direct or indirect path connecting them unless we condition on _Quiz_.
    - **Conditioning on Quiz:** _Study_ and _Sleep_ become **dependent** when you condition on _Quiz_. This is known as **"explaining away"**—knowing about _Quiz_ performance creates a dependency between _Study_ and _Sleep_.
### Bottom Graph:
- This is a **fork** structure, where _Sleep_ is a common cause of both _Race_ and _Quiz_.
- **Conditional Dependence:**
    - **Unconditionally:** _Race_ and _Quiz_ are **dependent** because they share a common cause (_Sleep_), creating a potential correlation.
    - **Conditioning on Sleep:** _Race_ and _Quiz_ become **independent** when you condition on _Sleep_ because the shared cause is accounted for.
![[Pasted image 20250206160102.png]]

### Variance
![[Pasted image 20250206154535.png]]
![[Pasted image 20250206154546.png]]
