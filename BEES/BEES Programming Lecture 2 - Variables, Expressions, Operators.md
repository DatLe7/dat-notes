## Notes

- Integer division in python uses double slashes ( // ) and one slash( / ) is normal division
- Shortcut to comment a lot of lines with # is ctrl + /

### Variables
- Variable is a named memory location
- It contains a value
- Variables refers to an object (IN PYTHON)
- = does not mean equal it means assignment
- Setting a variable equal to another variable means that they are now both referring to the same object (both x and y now refer to object "foo")
```
x = 1
y = "foo"
x = y
y = 5
```
- When we assign y to 5 we create a new object 5 that y now refers to. ( x still refers to foo)

### Variable Names
- Consist of numbers letter and _ (not -)
- Cannot start with a letter
- Cannot be one of the python reserved words
- Case sensitive (ex: Foo is different from FOO)

### Operators
- *Operator Overloading* means giving extended operator meanings for other purposes
```
x = "hi" * 5
x = 7 * 2
```

### Floor Division
- In Python floor division rounds to the lowest int (Does not cut off the decimal like java)

### Format Specifier
```
#Format scecifier
print('%.2f Fahrenheit is: %0.2f Celcius' %(temp_F, temp_C))
```