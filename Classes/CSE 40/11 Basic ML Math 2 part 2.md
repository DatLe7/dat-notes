### Date: 02-03-2025
### Instructor: Alexander Rudnick


## Notes:

### What is correlation?
The tendency for two values or variables to change together, in either the same or opposite way.
![[Pasted image 20250205075013.png]]
- If variables are correlated, they're not independent.  eg if X and Y are correlated, then P(Y|X) != P(Y) (and vice-versa, P(X|Y) != P(X) )
![[Pasted image 20250205075119.png]]
- Correlation also means that the two variables must be conditionally dependent

### Causality
*Definition*:  Influence by which one event, process, state, or object (a cause) contributes to the production of another event, process, state, or object (an effect) where the cause is partly responsible for the effect, and the effect is partly dependent on the cause. 
- In general, a process has many causes, which are also called *causal factors* for it, and all lie in its past.
- *An effect* can in turn be a cause of, or causal factor for, many other effects, which all lie in its future.

#### What is Casual Manipulation
![[Pasted image 20250205075343.png]]
- Changing one variable but keeping everything else the same and seeing if it affects an effect. Repeat this with a treatment and control group

### Two Distinct Approaches

#### Randomized Controlled Trial (RCT)
- In a RCT, a group of subjects is randomly partitioned into the *control* group and a *treatment* group.  
- Participants do not know which group they were assigned, and neither do the people administering the trial (*double-blind design*).
- The treatment group receives an actual *treatment*, such as the drug being tested, while the control group receives a *placebo*.
- An *outcome* variable is measured for all subjects.
![[Pasted image 20250205075636.png]]

#### A/B Testing
- A way to compare two versions of something to figure out which performs better.
	- Often associated with websites and apps.
- In the 1920s, statistician and biologist Ronald Fisher ran agricultural experiments, asking questions such as: 
	- What happens if I put more fertilizer on this land? 
- In the early 1950s, scientists started running clinical trials in medicine.
- In the 1960s and 1970s, the concept was adopted by marketers to evaluate direct response campaigns (e.g., would a postcard or a letter to target customers result in more sales?).

![[Pasted image 20250205075842.png]]
![[Pasted image 20250205075854.png]]
![[Pasted image 20250205075914.png]]

### CORRELATION vs. CAUSATION and CONFOUNDERS
![[Pasted image 20250205080000.png]]
![[Pasted image 20250205080037.png]]
- In each of these examples the confounding factor would be Cavity, Raining, Fire
