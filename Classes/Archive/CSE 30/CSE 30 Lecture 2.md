## Notes

### Hash Tables
- Hash table takes near constant time to look up a value
- If two keys hash to the same location a linked list will be created 
![[Pasted image 20241003173459.png]]
### Generators/Yield
- The yield statement suspends a function’s execution and sends a value back to the caller, but retains enough state to enable the function to resume where it left off. When the function resumes, it continues execution immediately after the last yield run. This allows its code to produce a series of values over time, rather than computing them at once and sending them back like a list.
``` python
def generate():
	yield 1
	yield 2
	yield 3

for value in generate():
	print(value)

# Results:
# 1
# 2
# 3
```
- We should use yield when we want to iterate over a sequence, but don’t want to store the entire sequence in memory. Yield is used in Python generators
``` python
def squares():
	i = 1
	# Will generate infinite amount of squares
	while true:
		yield i*i
		i += 1

#prints sqaures until 100
for square in squares():
	if square > 100:
		break
	print(square)
```
- You can have generators take parameters
### Paging
- When you have a large amount of data that need to be process, you would page it meaning you would split the data into smaller chunks and process those

### Quick Notes
- Using the in statement for list is very expensive, it is better to use the in statement as a set
