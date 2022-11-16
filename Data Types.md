# Data Types
## What is Data Types ?
```
Ans: A data type is a set of possible values and a set of allowed operations on it. A data type tells the compiler or interpreter how the programmer intends to use the data.
          *** Use the type() function to know which class a variable or a value belongs to ***
```
![image](https://user-images.githubusercontent.com/116889143/202220031-c6af0be6-740d-4c9a-86ac-b4dfb11c8f7d.png)

## How many Data types in Python ?
```
Ans : Python has six standard Data Types . There are ,

(1) Number 
(2) String
(3) List
(4) Set
(5) Tuple
(6) Dictionary.

```
![image](https://user-images.githubusercontent.com/116889143/202224107-cf8efc93-87aa-43b9-b2a5-093aebb50aaf.png)


# (1) Number 

Python supports 3 different numerical types −
- int (signed integers)
- float (floating point real values)
- complex (complex numbers)

![Python-Number-Types-01-1024x536](https://user-images.githubusercontent.com/116889143/202227316-90a43c04-4f3c-48af-a34c-b1241c8f96a9.png)
![image](https://user-images.githubusercontent.com/116889143/202227887-8d8084fb-8f2e-4c2e-933c-585c84dfcda6.png)

```python
Input :

a = 12
print(a, "is of type", type(a))
a = 94.32
print(a, "is of type", type(a))
a = 1+2j
print(a, "is complex number?", isinstance(1+2j,complex))

Output :

12 is of type <class 'int'>
94.32 is of type <class 'float'>
(1+2j) is complex number? True
```

# (2) String

A string is a collection of one or more characters put in
- a single quote ( name = 'This is Python Course')
- double-quote ( name = "This is Python Course")
- triple quote ( name = '''This is Python Course''')
```
In python there is no character data type, a character
is a string of length one. It is represented by str class.
```


```python
Input :

name1 = 'This is Python Course'
name2 = "This is Python Course"
name3 = '''This is Python Course'''
print(name1)
print(name2)
print(name3)

Output:

This is Python Course
This is Python Course
This is Python Course

```
![image](https://user-images.githubusercontent.com/116889143/202230546-148475a3-246f-4829-8350-007aa5bfc64f.png)

