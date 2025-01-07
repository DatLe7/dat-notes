
## Notes:

- To access the last element in a list you would index -1 (THIS IS ONLY PYTHON)
`list[-1]`
- To access elements in a range you would do this: (THIS IS ONLY PYTHON). 1st index is included last index is excluded
`list[1:3]`
- You can splice list too with this too
``` python
list[1:] #access index 2 and all values after that index
list[:3] #access all values before index of 3 not including it
```
- When modifying a list a new object is not created for the list to now point to. When you modify the list variable points to the same object and the value of the object is modified.
- When you create a new variable and set it to a list variable, they would both point to the same list object. So when you modify an index value in one of the list variable, the index value would be changed for both list variables because the object is modified and they both point to the same object
- To stop this from happening you must make a deep copy or a clone (create a new list and copy every element using)
`chill = cool[:]`
- ex:
``` python
cool = ["blue", "green", "grey"]
chill = cool[:]
cool.append("yellow")
print(cool)
print(chill)
```
``` python
#Results
['blue', 'green', 'grey', 'yellow']
['blue', 'green', 'grey']
```
- Use `list.extend([1, 2, 3])` to add multiple elements to a list or to combine 2 lists

- You can access individual characters in a string using indices
``` python
word = "Hello"
character = word[0] # Value is now 'H'
```
- You can also splice strings with substrings
``` python
word = "Hello"
slice1 = word[1,3] # Value is now "el"
slice2 = word[:3] # Value is now "Hel"
slice3 = word[1:] # Value is now "ello"
```
- To modify strings you have to create a new string