### Date: 02-5-2025
### Instructor: Jiayin Pan


## Notes:

### Effect of Row Operations on Determinant
![[Pasted image 20250210184401.png]]
**Reminder:** Let $A,B\in M_{2x2}$. If either A or B is singular (i.e. not invertible) then AB is singular
- Meaning if A or B is singular then the det(AB)=0
- having a zero determinant means that the matrix is singular
$\det (ab)=\det(a)\cdot \det(b)$
### Determinant Properties
![[Pasted image 20250210184849.png]]
1. If $P_{i}=(0\dots0)$, then detA=0
2. det($I_{n}$)=1
3. If you switch 2 rows in A and get B, then detB=-detA
4. If you scale one row by c then get B, then detB=c$\cdot$detA
5. If you apply row addition to A and get B, then detB=detA
6. If the rows in A are linearly dependent then det(RREF)=0, hence detA=0
7. If detA=0, then 0.$p_{1}\dots p_{n}$ determines degraded area, then A is singular
8. E elementary Matrix
	- E from row switching       detE=-1(=det$E^T$)
	- E from row scaling by c    detE=c(=det$E^T$)
	- E from row addition         detE=1(=det$E^T$)
9. det(AB)=detA$\cdot$detB
10. detA=det$A^T$

### Solving for Determinant
![[Pasted image 20250210185641.png]]
- Method 1: top row element times the determinant of the matrix formed by excluding the row and column of the top row element

#### Examples
1. ![[Pasted image 20250210185701.png]]
2. ![[Pasted image 20250210185712.png]]
3. ![[Pasted image 20250210185720.png]]
