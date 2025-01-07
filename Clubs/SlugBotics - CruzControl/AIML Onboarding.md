
## Notes:

### BFS VS DFS (Breadth vs Depth (First Search))
![[Pasted image 20241012164101.png]]

- DFS search deep in each branch while BFS searches layer by layer

### A* Algorithm
- similar to Dijkstra's algorithm
![[Pasted image 20241012164738.png]]

### Probabilistic and Fuzzy Logic
- Probabilistic Logic is how confident you are in the next state (represented in a floating point number)
- The certainty is represented by three states certain, maybe and not. ???
- Probabilistic logic allows you to take the derivative so you can get insight on if you are getting closer or farther away.

### Reinforcement Learning
![[Pasted image 20241012170618.png]]
- Q Learning: Q value represents the value of taking a certain action during a certain state
- Q represents Quality and help to find the best possible action given a certain state to maximize future rewards
- When looping, Q value is updated depending on the rewards given when taking a certain action
![[Pasted image 20241012172034.png]]
- Utility Function (U(s)) is the expected value associated with taking an action in a certain state
- Sometimes pick a random action that is not the best Q value so the learning can take place and explore more to get to possible better actions
- To update a Q value you take the initial estimate that the machine had and add the given reward to the Q value
- End goal will have the highest utility function value and everything approaching it will have less
