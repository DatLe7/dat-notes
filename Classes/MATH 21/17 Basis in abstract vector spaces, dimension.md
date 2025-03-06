### Date: 02-19-2025
### Instructor: Jiayin Pan


## Notes:
### Checking If a Set is a Basis
![[Pasted image 20250223120745.png]]
- This is saying that if we can make a vector w with a linear combination of $v_{i}$ then we can also make the coordinate vector for that vector w by swapping $v_{i}$ with there coordinate vectors $[v_{i}]_{\mathbb{B}}$ 

![[Pasted image 20250223121301.png]]
![[Pasted image 20250223121311.png]]
- To find out if a set is a basis. We use the standard basis for the abstract vector space and find the coordinate vector based off the standard basis for each element in the set 
- we then can form it into a matrix and check the determinant to see if it is linearly independent/basis

#### Examples
1. ![[Pasted image 20250223121715.png]]
2. ![[Pasted image 20250223121725.png]]
3. ![[Pasted image 20250223121734.png]]

### Changing Basis
![[Pasted image 20250223122614.png]]
![[Pasted image 20250223122628.png]]
- In order to change basis from $\beta \to \alpha$ we take the basis of $\alpha$ and find the coordinate vector based off the basis $\beta$ for each element in $\alpha$


#### Example
![[Pasted image 20250223123601.png]]

### Properties
![[Pasted image 20250223123635.png]]
![[Pasted image 20250223123647.png]]
- A change of basis can find the coordinate vector of another basis given you have the coordinate vector of a starting basis
- $[w]_{b}=P^a_{b}[w]_{a}$
- Inverting a change of basis flips it
- $(P^a_{b})^{-1}=P^b_{a}$

- $P^b_{e}\cdot P^a_{b}=P^a_{e}$
- This is because it first changes basis from a to b, then changes from b to e. This is the same thing as going from a to e but with extra steps so they are equivalent
