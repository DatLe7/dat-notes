### Date: 02-5-2025
### Instructor: Alexander Rudnick


## Notes:

### Simpson's Paradox
- *Simpson's paradox* is a phenomenon in probability and statistics, in which a trend appears in several different groups of data but disappears or reverses when these groups are combined. 

- For instance, two variables may be positively associated in a population, but be independent or even negatively associated in all subpopulations.
- Cases exhibiting the paradox are unproblematic from the perspective of mathematics and probability theory, but nevertheless strike many people as surprising.

### Basic Causal Diagrams
Y = acceptance
A = female
Z = department
![[Pasted image 20250210182126.png]]

Controlling for the effect of Department:
- if we have R (state of residence), which confounds Z and Y, then Z introduces dependence,  and if we condition on department, we do not get the desired direct effect
![[Pasted image 20250210182149.png]]

An alternative possibility is that the reason for the differences in department choice is related to fear of discrimination (F).   
**Possibilities**:
	Department may have advertised the program in a manner that strongly discourages women from applying.
	Department could have a track record of hostile behavior against women, and awareness of this could shape applicants’ preferences.
	Blatant discrimination, such as lower pay, could be happening.
	Saying that the indirect path is non-discriminatory means that we are asserting that none of these reasons are plausible.
![[Pasted image 20250210182221.png]]

#### Power of Causal Models
- **The three models we just proposed are all consistent with the data.**

- The power of causal models is that they give us a means of articulating the different possible mechanisms and factors.

- At this point, more information is needed, from domain experts, further studies, etc.

- In any case, this all calls into question the original decision made in the Berkeley admissions case -- situation wasn't as simple as it seemed!

### Biased Data
- **Selection bias** occurs when there are systematic differences between subsets of data, such that the subset is not representative of the overall population.
- **Sampling bias** can happen when some subsets are excluded from the research sample for one reason or the other, leading to imbalanced representation of the different subgroups in the sample population. 
- **Exclusion bias** happens when the researcher intentionally removes some subgroups from the sample population. 
- **Attrition bias** happens when some research participants exit the study while it’s still ongoing.  If this happens differentially for different subpopulations, this affects the quality of the outcomes arrived at in the end. 

#### Examples
- **Example 1**:   During educational research, the investigator only collects responses from students who arrive at school before a particular time. This excludes people who do not meet the required time, even if their experience is relevant.  **Sampling bias**.
- **Example 2**:  When conducting clinical research, investigator includes only the healthy young adults from the trials, even though the disease predominantly affects the older population.  **Exclusion bias**.
- **Example 3**: Facial recognition only trained on white faces.  **Exclusion bias**.
- **Example 4**: A study has three separate phases. After the second phase, some of the participants refuse to continue with the process, leading to **attrition bias**. 

#### Survivorship Bias
- Survivorship bias means that the researcher screens subjects and chooses the ones who pass the screening process successfully. 
- This preselection process pushes out unsuccessful subjects due to their lack of visibility.  

#### More Examples
- **Example 1**:   During educational research, investigator only collects responses from students who arrive at school before a particular time. It excludes people who do not meet the required time, even if their experience is relevant.  **Survivorship bias**
- **Example 2**:  When conducting clinical research, investigator includes only healthy young adults in the trials whereas the disease predominantly affects the older population.  **Survivorship bias/Exclusion bias**.
- **Example 3**: Facial recognition only trained on white faces.  **Exclusion bias**.
- **Example 4**: A study has three separate phases. After the second phase, some of the participants refuse to continue with the process, leading to **attrition bias**. 
