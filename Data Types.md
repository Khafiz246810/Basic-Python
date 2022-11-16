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

## What is the difference between these Three type of Quotes??

Ans:
- We can use single quotes or double quotes to represent strings.
-  Multi-line strings can be denoted using triple quotes, ''' or """

```python
Input :

name1 = 'This is Python Course'
print(name1)

Output: 
This is Python Course
```
```python
Input :

name1 = "This is Python Course"
text = "This is Khafiz’s Book"
print(name1)
print(text)

Output:

This is Python Course
This is Khafiz’s Book

```

```python
Input:

name3 = '''A multiline
string'''
print(name3)

Output:

A multiline
string
```

## Slice operator
- Slice operator ([ ] and [:] ) Beginning index at 0 and Backward index -1.
![image](https://user-images.githubusercontent.com/116889143/202252005-bde2609d-3d81-41ca-8749-752325cf9eb7.png)

```python
Input:

str = 'Hello World'
print (str) # Prints complete string
print (str[0]) # Prints first character of the string
print (str[2:5]) # Prints characters starting from 3rd to 5th
print (str[2:]) # Prints string starting from 3rd character
print(str[-1]) # # Prints the last character
print(str[-3:]) # # Prints the last character
print(str[:-3]) # # Prints the last character

Output:

Hello World
H
llo
llo World
d
rld
Hello Wo

```

![image](https://user-images.githubusercontent.com/116889143/202251268-fede50a5-6c48-45a2-be28-6fbc65913ace.png)


# Datatype Conversion 
```
You can explicitly check and convert the type of a
variable (for built-in data types).
```
```python
Input:

x = 50
print(type(x))
y = 'Python'
print(type(y))

Output:

<class 'int'>
<class 'str'>
```
![Screenshot 2022-11-16 at 23-37-04 Datatype Conversion in Python data types - Google Search](https://user-images.githubusercontent.com/116889143/202253074-61007cec-a830-4f3a-89a5-77a9dddc3300.png)


# Checking input types / Typecasting

![Type-Casting-in-Python](https://user-images.githubusercontent.com/116889143/202255794-4e22aa89-be1d-4ee2-b574-750323c5f094.png)


## How the input function works in Python :
Whatever you enter as input, input function convert it into a string. a.
  -  if you enter an integer value still input() function convert it into a string.
  -  You need to explicitly convert it into an integer in your code using typecasting.
  
  ```python
  Input:
  
num = input ("Enter number :")
print(num)
name1 = input("Enter name : ")
print(name1)
# Printing type of input value
print ("type of number", type(num))
print ("type of name", type(name1))

Output:

Enter number :42
42
Enter name : Khafiz
Khafiz
type of number <class 'str'>
type of name <class 'str'>
```
```python
Input:

x = input("1st number: ")
y = input("2nd number: ")
z = x + y
print('sum is: ', z)
print(type(x))
print(type(y))

Output:

1st number: 10
2nd number: 20
sum is:  1020
<class 'str'>
<class 'str'>

```
This is wrong Output . So we can solve this problem this way :
```python

Input:

x = input("1st number: ")
y = input("2nd number: ")
x = int(x)
y = int(y)
z = x + y
print("sum is: ", z)
print(type(x))
print(type(y))

Output:

1st number: 10
2nd number: 20
sum is:  30
<class 'int'>
<class 'int'>
```





