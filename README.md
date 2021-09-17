## [**Python Tutorial**](https://www.youtube.com/watch?v=rfscVS0vtbw&t=2078s)
____
### **Intro**

* _Python_ is a programing language.
* Need a _text editor_ to write code in (notepad, text edit, etc.)
>Note: There are special text editors for writing python code called IDE's (integrated develepment environments), we will use _PyCharm_.
____
### **Variables**
* A _variable_ is a container where we can store certain data types.
    ```python
    variable_name = "some value"
    ```
____
### **Data Types**

* **Strings** - Store text. Must be written in quotations.
    ```python
    character_name = "Tom"
    ```
* **Numbers** - Store whole or decimal numbers. 
    ```python
    character_age = 50
    ```
* **Boolians** - Store True or False value.
    ```python
    is_male = True
    ```
>Note: Can adjust data types in middle of code.
____
### **Working With Strings**
\
**Example 1:** We can use the print function to print different data types (strings in this case).

```python
print("Giraffe Academy")
```
>_Returns:_ Giraffe Academy

\
**Example 2:** We can store this string value inside of a variable (phrase).

```python
phrase = "Giraffe Academy"
print(phrase)
```
>_Returns:_ Giraffe Academy

\
**Example 3:** Concatination is the process of joining strings together.

```python
phrase = "Giraffe Academy"
print(phrase + "is cool")
```
>_Returns:_ Giraffe Academy is cool

\
**Example 4:** We can also use functions to modify/ get information, about our strings.
```python
phrase = "Giraffe Academy"
print(phrase_______)
```
|phrase(_______)  |Returns         |Description                                           |
| ---             | ---            | ---                                                  |
|.lower()         |giraffe academy |Converts entire string to lower case                  |
|.upper()         |GIRAFFE ACADEMY |Converts entire string to upper case                  |
|.islower()       |False           |Checks if phrase is lower case and returns a T/F value|
|.isupper()       |False           |Checks if phrase is upper case and returns a T/F value|
|[0]              |G               |Returns string value corresponding to its index number|
|.index("G")      |0               |Returns index number corresponding to its string value|
|.replace("G","J")|Jiraffe Academy |Functions as a search and replace                     |
|                 |                |                                                      |
>Note: Index numbers are assigned begining at 0 (i.e. G = 0, i = 1, r = 3, etc.)

\
**Example 5:** Functions can be used in combination with eachother.
```python
phrase = "Giraffe Academy"
print(phrase.upper().isupper())
```

>_Returns:_ True

\
**Example 6:** The length function will return the length of a string.
```python
phrase = "Giraffe Academy"
print(len(phrase))
```
>_Returns:_ 15

\
**Example 7:** Backslashes can be used in various ways to modify the output.

|print("______")  |Returns         |Description                         |
| ---             | ---            | ---                                |
|Giraffe Academy  |Giraffe Academy |Prints string with a space inbetween|
|Giraffe\\"Academy|Giraffe"Academy |Prints quotation mark               |
|Giraffe\\Academy |Giraffe\Academy |Prints string with a backslash      |
|Giraffe\nAcademy |Giraffe         |Prints string on a new line         |
|                 |Academy         |                                    |
|                 |                |                                    |

>Note: A backslash is called the escape character; meaning that whatever character comes after it we want to render literally.
___
### **Working With Numbers**
\
**Example 1:** We can use the print function to cary out various mathematic equations and print the results.
```python
print(10 _ 3)
```
|print(10 _ 3)|Returns|Description                       |
|:---:        |:---:  |---                               |
|+            |13     |Addition                          |
|-            |7      |Subtraction                       |
|/            |3.333  |Division                          |
|*            |30     |Multiplication                    |
|%            |1      |Modulus operator returns remainder|
|             |       |                                  |
>Note: Parentheses can be used to specify order of operations.

>Note: Python can handle whole numbers, decimal numbers and negative numbers.

\
**Example 2:** Common functions using numbers.
```python
num = -5
print(______)
```
|print(______)|Returns|Description                     |
|:---:        |:---:  |---                             |
|num          |-5     |Returns variable in integer form|
|str(num)     |-5     |Returns variable in string form |
|abs(num)     |5      |Returns absolute value          |
|pow(3,2)     |9      |3^2                             |
|max(3,2)     |3      |Returns larger number           |
|min(3,2)     |2      |Returns smaller number          |
|round(3.2)   |3      |Rounds input                    |
|             |       |                                |

>Note: You need to convert numbers into strings in order to print them alongside strings.

\
**Example 3:** In order to access certain functions we need to import python math.
```python
from math import*
print(______)
```
|print(______)|Returns|Description         |
|:---:        |:---:  |---                 |
|floor(3.7)   |3      |Cuts off lower value|
|ceil(3.7)    |4      |Rounds up           |
|sqrt(36)     |6      |Returns square root |
|             |       |                    |
___
### **How to get user input**
\
**Example 1:** Prompts user for name and age and returns input alongside strings.
```python
name = input("Enter your name: ")
age = input("Enter your age: ")
print("Hello " + name + "! You are " + age)
```
>_Returns:_ Hello Ashley! You are 31

\
**Example 2:** Prompts user for two numbers and returns their sum.
```python
num1 = input("Enter a number: ")
num2 = input("Enter another number: ")
result = float(num1) + float(num2)
print(result)
```
>Note: Both num1 and num2 are stored in string form and therefore must be converted into either integer (for whole numbers) or float form(for decimal numbers).
___
### **Dealing with Lists**
\
**Example 1:**
```python
friends = ["Kevin", "Karen", "Jim", "Oscar", "Toby"]
print(_______)
```
|print(______)|Description                              |
|:---:        |---                                      |
|friends      |Prints entire list                       |
|friends[0]   |Prints name corresponding to index number|
|friends[1:]  |Prints index 1 and all elements after    |
|friends[1:3] |Prints from index 1 up to index 3        |
|             |                                         |

\
**Example 2:**
```python
friends = ["Kevin", "Karen", "Jim", "Oscar", "Toby"]
friends[1] = "Mike"
print(friends[1])
```
>Note: This will modify index 1 (karen) and instead print Mike.
___
### **List Functions**
\
**Example 1:**
```python
lucky_numbers = [4,8,15,16,23,24]
friends = ["Kevin", "Karen", "Jim", "Oscar", "Toby"]
friends______
print(friends)
```
|friends______         |Description                   |
|:---:                 |---                           |
|.extend(lucky_numbers)|Add lists together            |
|.append("Creed")      |Add element to list           |
|.insert(1,"Kelly")    |Insert element into list      |
|.remove("Jim")        |Remove element from list      |
|.clear()              |Remove all elements from list |
|.pop()                |Removes last element from list|
|.sort()               |Sorts in alphabetical order   |
|.reverse()            |Reverses list                 |
|                      |                              |

\
**Example 2:**
```python
lucky_numbers = [4,8,15,16,23,24]
friends = ["Kevin", "Karen", "Jim", "Oscar", "Toby"]
friends2 = friends.copy()
print(friends2)
```
\
**Example 3:**
```python
lucky_numbers = [4,8,15,16,23,24]
friends = ["Kevin", "Karen", "Jim", "Oscar", "Toby"]
print(______)
```
|print(______)       |Definition                                               |
|---               |---                                                      |
|friends.count("Jim")|Counts the number of times an element appears in the list|
|friends.index("Jim")|Searches for a type of element in the list               |
|                    |                                                         |
___
### **Tuples**
\
**Example 1:** Prints coordinates coresponding to a specific index number.
```python
coordinates(4,5)
print(coordinates[0])
```
>_Returns:_ 4

\
**Example 2:** Touples are immutable, meaning they cannot be changed or modified.
```python
coordinates(4,5)
coordinates[1] = 10
print(coordinates[1])
```
>_Returns:_ TypeError: 'tuple' obj. does not support item assignment.
___
### **Tuples V.S. Lists**

|Tuples|Lists|
|---|---|
|Coordinates are stored in **parentheses ( )**|Coordinates are stored in **square brackets [ ]**|
|Tuples are **immutable**, meaning they cannot be changed.|Lists are **mutible**, meaning we can assign different values to them, mutate any of the elements, add, delete, modify or change.|
|||
___
### **Functions**
* A function is a collection of code that performs a specific task.
* Some functions are already available and can be called using their name.
* For all other tasks, we can create our own.

\
**Example 1:**
```python
def say_hi():
    print("Hello User")

say_hi()
```
>_Returns:_ Hello User

\
**Example 2:**
```python
def say_hi(name,age):
    print("Hello " + name + ", you are " + str(age))

say_hi("Mike",35)
```
>_Returns:_ Hello Mike, you are 35

>Note: You can pass age through as a string ("35") or a number (35) converted into a string.
___
### **Return Statement**
\
**Example 1:** Simple function containing a single parameter, designed to take in and cube a number.
```python
def cube(num):
    return num*num*num

print(cube(3))
```
>_Returns:_ 27

\
**Example 2:** We can also store our function inside a variable.
```python
def cube(num):
    return num*num*num

result = cube(3)
print(result)
```
>_Returns:_ 27

>Note: The return keyword breaks out of the function automatically; therefore, you cannot add code following the return statement.
___
### **If Statements**
\
**Example 1:** Program using if statements; will respond to boolean input.
```python
is_male = ______
is_tall = ______

if is_male and is_tall:
    print("You are a tall male")
elif is_male and not(is_tall):
    print("You are a short male")
elif not(is_male) and is_tall:
    print("You are not a male, but you are tall")
else:
    print("You are not a male and not tall")
```
|is_male|is_male|Returns|
|:---:|:---:|---|
|True|True|You are a tall male|
|True|False|You are a short male|
|False|True|You are not a male, but you are tall|
|False|False|You are not a male and not tall|
|||

>Note: If both conditions are met, the code will be executed; otherwise, it will move onto the next line of code.

>Note: Can use "or" if you only require one condition to be met.
___
### **If Statements and Comparisons**

\
**Example 1:**
```python
def max_num(num1,num2,num3):
    if num1 >= num2 and num1 >= num3:
        return num1
    elif num2 >= num1 and num2 >= num3:
        return num2
    else:
        return num3

print(max_num(3,40,5))
```
>_Returns:_ 40

\
**Table 1:** Other comparison Opperators
|Comparison Operators|Definition|
|:---:|---|
|>=|Greater than or equal too|
|<=|Less than or equal too|
|==|Equal|
|!=|Not equal|
|||
___
### **Building a Better Calculator**
\
**Example 1:**
```python
num1 = float(input("Enter first number: "))

op = input("Enter operator")

num2 = float(input("Enter second number: "))

if op == "+":
    print (num1 + num2)
elif op == "-":
    print(num1 - num2)
elif op == "/":
    print(num1/num2)
elif op == "*":
    print(num1*num2)
else:
    print("Invalid Operator")
```
___
### **Dictionary**
*Special structure in python that allows us to store key-value pairs.
\
**Example 1:** Convert three digit month abreviation into full month name.
```python
month_conversions = {
    "Jan" : "January",
    "Feb" : "February",
    "Mar" : "March",
    "Apr" : "April",
    "May" : "May",
    "Jun" : "June",
    "Jul" : "July",
    "Aug" : "August",
    "Sep" : "September",
    "Oct" : "October",
    "Nov" : "November",
    "Dec" : "December",
}

print(month_conversions["Nov"])
```
>_Returns:_ November

\
**Example 2:** Can specify a default value if key is not found.
```python
month_conversions = {
    "Jan" : "January",
    "Feb" : "February",
    "Mar" : "March",
    "Apr" : "April",
    "May" : "May",
    "Jun" : "June",
    "Jul" : "July",
    "Aug" : "August",
    "Sep" : "September",
    "Oct" : "October",
    "Nov" : "November",
    "Dec" : "December",
}

print(month_conversions.get("Luv","Not a valid key"))
```
>_Returns:_ Not a valid key
___
### **While Loops** 
\
**Example 1:**
```python
i = 1
while i <= 10:
    print(i)
    i = i + 1
```
>_Returns:_ 1-10

>Note: You can also use i += 1 (shorthand notation)
___
### **Build a Guessing Game**
\
**Example 1:** Guess the secret word.
```python
secret_word = "Giraffe"

guess = ""

while guess != secret_word:
    guess = input("Enter guess: ")

print("You win!")
```
>Note: Game will continue to prompt the user to guess the secret word until they get it right. Once they guess the secret word, it will print "You win!".

\
**Example 2:** You get three tries to guess the secret word.
```python
secret_word = "Giraffe"

guess = ""

guess_count = 0

guess_limit = 3

out_of_guesses = False

while guess != secret_word and not(out_of_guesses):
    if guess_count < guess_limit:
        guess = input("Enter guess: ")
        guess_count += 1
    else:
        out_of_guesses = True

if out_of_guesses:
    print("Out of guesses, YOU LOSE!")
else:
    print("You win!")
```
>Note: The user will be given three tries to guess the secret word.  If they guess the secret word in three guesses or less, it will print "You win!"; otherwise, it will print "YOU LOSE!".
___
