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
- The top one is conditionally independent because if we did good on the quiz and we studied then that tells us nothing about how well we slept because we already have an explanation for why we did good on the test
- The bottom one is conditionally dependent because if we did well on the race then we know we must have slept well meaning that we also must have done good on the quiz
