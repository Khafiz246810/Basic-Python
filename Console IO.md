# Running Python in Command-Prompt
![1 de3JlVavp6Fs_tVNoztb6Q](https://user-images.githubusercontent.com/116889143/201987018-03655321-01c2-4031-bc7b-c5db69ff0d5c.png)

# Display values to the Console ()

## (1) print() statement prints / displays information in the console.
```python
Input:
print("Hello World ! I am trying to learn Python!!")
Output:
Hello World ! I am trying to learn Python!
```
![Screenshot 2022-11-16 at 00-05-57 Google Colaboratory](https://user-images.githubusercontent.com/116889143/201993612-8d4844fe-8aa2-45ce-b74a-b902ee4dadae.png)

## (2) Use the print() Statement to Print a Variable in Python
```python
Input:
var = "Hello World !"
print(var)

Output :
 Hello World ! 
```
![Screenshot 2022-11-16 at 00-07-33 Google Colaboratory](https://user-images.githubusercontent.com/116889143/201993865-f671add0-a4f2-48f8-b21f-5ed487dcfee5.png)

 ## (3) Print multiple variables: Use a Comma , to Separate the Variables and Print Them
 
 ```python
 Input:
 var1=3242
 var2= "earth "
 parint("Hello to the ",var2,var1)
 
 Output:
 Hello to the  earth 3242
 ```
 ![Screenshot 2022-11-16 at 00-10-36 Google Colaboratory](https://user-images.githubusercontent.com/116889143/201995262-e99bcb2a-6f50-4981-bb86-e140fa5a7c4b.png)

## (4)Use the String Formatting With the Help of {} 

``` python
Input :
name = "Khafiz"
id = 2229323
print("Welcome {} with id {} to the class".format(name,id))

Output :
Welcome Khafiz with id 2229323 to the class
```
![Screenshot 2022-11-16 at 00-25-10 Google Colaboratory](https://user-images.githubusercontent.com/116889143/201997141-2b0a27b8-2600-400b-af72-7b130f888ddc.png)

## (5) Use the f-string in the print Statement

```python
Input:
name = "Khafiz"
id = 2229323
print(f"Welcome {name} with id {id} to the class")

Output:
Welcome Khafiz with id 2229323 to the class
```
![Screenshot 2022-11-16 at 00-27-53 Google Colaboratory](https://user-images.githubusercontent.com/116889143/201997581-3951f228-8eda-4ddc-8a62-83098d073fc2.png)

# Working with user Input 
## (1)Taking input from user: input(prompt) function

```python
Input:
name = input("Enter your name: ")
print(name)

Output:
Enter your name: Khafiz
Khafiz
```
![Screenshot 2022-11-16 at 00-32-31 Google Colaboratory](https://user-images.githubusercontent.com/116889143/201998429-be191bca-6352-41a7-b846-68ccc283708a.png)

## How the input function works in Python :
```
i. When input(prompt) function executes program flow will be stopped until the user has given an input.
ii. The text or message display (i.e., the prompt) on the output screen is optional. 
iii. Whatever you enter as input, input function convert it into a string. 
iv. if you enter an integer value still input() function convert it into a string.
v. You need to explicitly convert it into an integer in your code using typecasting.
```
# Comments in your program ( Comments are not printed!!) 
```
i. A hash sign (#) that is not inside a string literal is the beginning of a comment.
ii. All characters after the #, up to the end of the physical line, are part of the comment.
iii. The Python interpreter ignores them while executing the code.
```

```python
Input:
#First comment
print ("Hello, Python!") # second comment

Output:
Hello, Python!
```
![Screenshot 2022-11-16 at 00-37-49 Google Colaboratory](https://user-images.githubusercontent.com/116889143/201999314-81f18b30-2d9f-4a2c-ba46-8f9640a7d956.png)




