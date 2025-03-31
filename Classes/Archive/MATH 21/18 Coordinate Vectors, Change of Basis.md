### Date: 02-21-2025
### Instructor: Jiayin Pan


## Notes:
### Change of Basis
![[Pasted image 20250223124029.png]]
- We can set this problem up as $A\vec{x}=b$ problem and find to find the a,b,c values that make up the coordinate vector

### Linear Maps
![[Pasted image 20250223125010.png]]

### Examples
![[Pasted image 20250223125120.png]]
- Same as checking if maps were linear before just in different abstract vector spaces
![[Pasted image 20250223125415.png]]
![[Pasted image 20250223125440.png]]
![[Pasted image 20250223125508.png]]
- A linear map must always be able to map to the zero vector
![[Pasted image 20250223125639.png]]
![[Pasted image 20250223125911.png]]

### Kernel(Null Space) and Image(Range)
![[Pasted image 20250223130115.png]]
 - The Kernel is the set of all inputs into the linear map to gives the zero vector as an output
 - The Image is the set of all possible output vectors from applying the linear map to some input vector 
### Examples
![[Pasted image 20250223130206.png]]
![[Pasted image 20250223130216.png]]


### Injective, Surjective, Bijective
![[Pasted image 20250223130423.png]]
- Injective means that each vector inputted into the linear map has one distinct output meaning there are no inputs that give the same output
- In terms of a set of vectors. Injective means that it has to be a basis because there can only be one coordinate vector for each vector in the dimension. If it is a spanning set but it is not injective then that means that it is linear dependent
- Surjective means that its set of all possible output vectors is the same its output dimension (i.e. it can output all vectors in its output dimension)
- In terms of a set of vectors, surjective means that it is a spanning set. It can output all vectors in its codomain
- Basically, injective means linearly independent and surjective means spanning set
- Bijective means a linear map is both injective and surjective
### Examples
![[Pasted image 20250223130441.png]]
- This is saying that if the map is linear then the kerT={0}
- This also makes sense because being injective means that there is only one vector in the domain that would map to another vector in the codomain. meaning that the zero vector can at most have one vector map to it
