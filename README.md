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
____
### **Working With Strings**
\
**Example 1:** We can use the print function to print different data types.

```python
print("Giraffe Academy")
```
>_Returns:_ Giraffe Academy

\
**Example 2:** We can store a string inside of a variable .

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
|print(______)|Returns|Description                                             |
|:---:        |:---:  |---                                                     |
|num          |-5     |Returns variable in integer form                        |
|str(num)     |-5     |Returns variable in string form                         |
|abs(num)     |5      |Returns absolute value                                  |
|pow(3,2)     |9      |Raises the first input to the power of the second input |
|max(3,2)     |3      |Returns larger number                                   |
|min(3,2)     |2      |Returns smaller number                                  |
|round(3.2)   |3      |Rounds input                                            |
|             |       |                                                        |

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
>Note: More functions requiring the math module can be found [here](https://docs.python.org/3/library/math.html).
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
>Note: Python will convert user input into a string by default; therefore num1 and num2 must be converted into either integer (for whole numbers) or float form (for decimal numbers).
___
### **Dealing with Lists**
\
**Example 1:** Common ways to access elements from a list.

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
>Note: Negative numbers can be used to access elements from the back of the list.

\
**Example 2:** We can also modify elements from our list.

```python
friends = ["Kevin", "Karen", "Jim", "Oscar", "Toby"]

friends[1] = "Mike"

print(friends[1])
```
>Note: This will modify index 1 (karen) and instead print Mike.
___
### **List Functions**
\
**Example 1:** Using functions to modify or get information about lists

```python
lucky_numbers = [4,8,15,16,23,24]

friends = ["Kevin", "Karen", "Jim", "Oscar", "Toby"]

friends______

print(friends)
```
|friends______         |Description                                    |
|---                   |---                                            |
|.extend(lucky_numbers)|Add lists together                             |
|.append("Creed")      |Add element to list                            |
|.insert(1,"Kelly")    |Insert element into list                       |
|.remove("Jim")        |Remove element from list                       |
|.clear()              |Remove all elements from list                  |
|.pop()                |Removes last element from list                 |
|.sort()               |Sorts list in ascending or alphabetical order  |
|.reverse()            |Reverses list                                  |
|                      |                                               |

\
**Example 2:** We can also copy our list

```python
lucky_numbers = [4,8,15,16,23,24]

friends = ["Kevin", "Karen", "Jim", "Oscar", "Toby"]

friends2 = friends.copy()

print(friends2)
```
\
**Example 3:** Other list functions

```python
lucky_numbers = [4,8,15,16,23,24]

friends = ["Kevin", "Karen", "Jim", "Oscar", "Toby"]

print(______)
```
|print(______)       |Definition                                               |
|---                 |---                                                      |
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
**Example 1:** Function that prints "Hello User" when called.

```python
def say_hi():
    print("Hello User")

say_hi()
```
>_Returns:_ Hello User

\
**Example 2:** Multi-parameter function that greets user depending on given user input.

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
**Example 1:** Function that takes in three parameters, compairs them and then returns the maximum value.

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
**Table 1:** Other comparison opperators

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
**Example 1:** The user is prompted to input two numbers and an operator of their choice. The following if statements cary out and print the corresponding calculation.

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
>Note: The numbers must be converted into float or integer form.
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

*Loops through code repeatedly, until set condition is false.

\
**Example 1:** The variable "_i_", is initially set equal to one. As long as "_i_" is less than or equal to ten python will loop through the code, printing the value of "_i_" and increasing its value by one.

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
### **For Loops**
* Used to loop through certain collections in python.

\
**Example 1:** Strings

```python
for letter in "Giraffe Academy":
    print(letter)
```
>Note: Prints the individual letters from "Giraffe Academy", each on a new line.

\
**Example 2:** Arrays

```python
Friends = ["Jim", "Karen", "Kevin"]

for friend in Friends:
    print(friend)
```
>Note: Prints names of friends on individual lines.

\
**Example 3:** Series of numbers

```python
for index in range (10):
    print(index)
```
>Notes: Prints numbers 0-9 on individual lines.

\
**Example 4: Range of numbers

```python
for index in range(3,10):
    print(index)
```
>Notes: Prints numbers 3-9 on individual lines.

\
**Example 5:** Find the length of an array

```python
friends = ["Jim", "Karen", "Kevin"]

print(len(friends))
```
>_Returns:_ 3
 
 \
 **Example 6:** Can set range using length function

 ```python
friends = ["Jim", "Karen", "Kevin"]

for index in range(len(friends)):
    print(friends[index])
```
>Note: Prints names of friends on individual lines.

>Note: Range is set to the length of the friends variable (0-3), printing friends cooresponding to the indicies 0, 1, and 2.

\
**Example 7:** You can use all kinds of logic inside for loops

```python
Friends = ["Jim", "Karen", "Kevin"]

for index in range(5):
    if index == 0:
        print("first iteration")
    else:
        print("not first")
```
>Note: Will print "first iteration" for index number 0, corresponding to Jim, and then "not first" for every subsequent index, up to 5 (four times).
___
### **Exponent Function**
\
**Example 1:** Shorthand power notation

```python
print(2**3)
```
>_Returns:_ 8

\
**Example 2:** Multi-parameter function using for loops to raise one input to another

```python
def raise_to_power(base_num,pow_num):
    result = 1
    for index in range(pow_num):
        result = result * base_num
    return result

print(raise_to_power(3,2))
```
>_Returns:_ 9

>Note: If pow_num is set to 2, the range will be from 0 up to 2 (0,1); meaning, python will run the for loop two times (corresponding to index 0 and 1).  On the first iteration the result will be set to 3 (1 x 3) and on the second iteration the result will be 9 (3 x 3). After two iterations, python will print the result.
___
### **2D Lists and Nested Loops**
\
**Example 1:** You can create a grid-like structure in python using 2D lists

```python
number_grid = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9],
    [0]
]

print(number_grid[2][1])

```
>_Returns:_ 8

>Note: Can access certain elements by indicating the row [2] and column [1] you want to access (remember to start counting at zero).

\
**Example 2:** Nested for loop

```python
 number_grid = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9],
    [0]
]

for row in number_grid:
    for col in row:
        print(col)
```
>Note: Will print each value in the 2D array on separate line.
___
### **Building a Translator**
* Takes in a string and converts it into another language.

    ```
    Giraffe Language
    vowels -> g
    - - - - - - - - - 
    dog -> dgg
    cat -> cgt
    ```
\
**Example 1:** We can create a function to simulate the Giraffe Language above

```python
def translate(phrase):
    translation = ""
    for letter in phrase:
        if letter in "AEIOUaeiou":
            if letter.isupper():
                translation = translation + "G"
            else:
                translation = translation + "g"
        else:
            translation = translation + letter
    return translation

print(translate(input("Enter a phrase:"))) 
```

>Note: Line four checks to see if there are any vowels in the string. We could also use...
```python
if letter.lower() in "aeiou":
```
___
### **Comments**
* Non-exicutable line of code, meant to provide insight into the file.

\
**Example 1:** Comments are written using hashes and typically provide clarifying information fot other developers

```python
#This program is cool
#This program prints out a new string 

print("Comments are fun")
```

\
**Example 2:** For multi-line comments we can use hashes for each new line, or we can sandwich the text in between two sets of three single quotation marks

```python
'''
This program is cool
This program prints out a string
'''

print("Comments are fun")
```
>Note: It is common practice to comment out a line of code when troubleshooting program errors.
___
### **Try Except**
* Method of catching errors in python.

\
**Example 1:** We can use **try** and **except** blocks to catch any input errors that may throw off our code

```python
try:
    number = int(input("Enter a number:"))
    print(number)
except:
    print("Invalid input")
```  

\
**Example 2:** In most cases the except block by itself is too broad, meaning it will except any errors.

```python
try:
    value = 10 / 0
    number = int(input("Enter a number:"))
    print(number)
except:
    print("Invalid input")
```
_Returns:_ Invalid input

\
**Example 3:** We can specify the types of errors we want to catch

```python
try:
    value = 10 / 0
    number = int(input("Enter a number:"))
    print(number)
except ValueError:
    print("Invalid input")
except ZeroDivisionError:
    print("Divided by zero")
``` 

 \
**Example 4:** We can also store a specific error as a variable

```python
try:
    value = 10 / 0
    number = int(input("Enter a number:"))
    print(number)
except ValueError:
    print("Invalid input")
except ZeroDivisionError as err:
    print(err)
``` 
>Note: This will print out the error that went wrong.
___
### **Reading Files**

\
**Example 1:** We can read files outside of python using the open function

_File 1: employees.txt_

```python
Jim - Salesman
Dwight - Salesman
Pam - Receptionist
Michael - Manager
Oscar - Accountant
```

_File 2: app.py_

```python
open("employees.txt", "__")
```

|open("employees.txt", "__")|Description|
|:---:|---|
|r|Read; can only read information, cannot modify or change file|
|w|Writing; you can change the file|
|a|Append; you can append information onto the end of the file, you cannot modify or change the file|
|r+|Read and write; you can read and change the file|
|||

>Note: The second parameter we want to include is the mode we want to open the file in.

>Note: Inside open, we can type the name of the file we want to open; that is a relative path to file, an absolute path to file, or just the file name if both files are in the same directory. In this case, employees.txt and app.py are in the same folder/directory so we can just use the name of the file.

\
\
**Example 2:** We can use functions to get information about an open file

_File 2: app.py_

```python
employee_file = open("employees.txt", "r ")

print(employee_file.__________)

employee_file.close()
```

|print(employee_file__________)|Definition|
|---|---|
|.readable()|Checks if file is readable and returns a boolian value|
|.read()|Reads the file and returns all of its contents|
|.readline()|Reads line one by default; if repeated it will read line two, etc.|
|.readlines()[1]|Takes all lines inside of file and puts them inside of a list. To access a specific line we can refer to its index number in the list; for example [1] corresponds to line 2 (Dwight - Salesman)|

>Note: We usually want to store an open file inside of a variable.

>Note: Once we are done reading a file we can use the close function to close it.

\
\
**Example 3:** We can also use the readlines function with a for loop

_File 2: app.py_

```python
employee_file = open("employees.txt", "r")

for employee in employee_file.readlines():
    print(employee)

employee_file.close()
```
>Note: Prints out each line in the file.
___
### **Writing to Files**

\
**Example 1:** Writing and appending external text files in python

_File 1: employees.txt_

```python
Jim - Salesman
Dwight - Salesman
Pam - Receptionist
Michael - Manager
Oscar - Accountant
```

_File 2: app.py_

```python
employee_file = open("employees.txt", "a")

employee_file.write("Toby - Human Resources")

employee_file.close()
```

>Note: Adds appended information to text file. 

>Note: Text will be appended onto an existing line if a new one isnt available in the text file. This can also be rectified by insertig a new line.

```python
employee_file.write("\nToby - Human Resources")
```

\
\
**Example 2:** We can override an external text file by opening it in write mode.

_File 2: app.py_

```python
employee_file = open("employees.txt", "w")

employee_file.write("Kelly - Customer Service")

employee_file.close()
```

>Note: This will replace the entire text file.

\
\
**Example 3:** We can also use write mode to create a new file

_File 2: app.py_

```python
employee_file = open("employees1.txt", "w")

employee_file.write("Kelly - Customer Service")

employee_file.close()
```

>Note: This will create a new text file called employees1.txt

\
\
**Example 4:** We can also use write mode to create a new web page

_File 2: app.py_

```python
employee_file = open("index.html", "w")

employee_file.write("<p>This is HTML<\p>")

employee_file.close()
```

>Note: HTML is a web page
___
### **Modules and Pip**

* Module - External python file that we can import into our current python file.

* Pip - Program used to install python modules; commonly refered to as a package manager because it allows you to install, manage and uninstall different python modules.

\
**Example 1:** Importing functionality from external python files 

_useful_tools.py_
```python
meters_in_kilometer = 1000
beatles = ["John Lennon", "Paul McCartney", "George Harrison", "Ringo Star"]

def get_file_ext(filename):
    return filename[filename.index(".") + 1:]

def roll_dice(num):
    return random.randint(1, num)
```

_app.py_
```python
import useful tools

print(useful_tools.roll_dice(10))
```
>Note: The import statement allows us to access all of the tools from the useful tools file.

>Note: Using the print function we can specify which variable or function we want to access.

>Note: We can access other useful python modules from the [python module index](https://docs.python.org/3/py-modindex.html), or search for third party modules online.

\
\
**Table 1:** Types of Modules
|Type|Definition|
|---|---|
|Built-in|Built into python language; we automatically have access to them|
|External|Stored in the same folder we installed python in on our computer|
|||

\
\
**How to install and use third party modules:**
1. Check to see if pip is installed using the terminal command:
    ```terminal
    pip --version
    ```

1. Install pip if no version is found.
    - Pip comes preinstalled with new version of python 3.
    
1. Find a python module you want to install.
    - e.g. [python-docx](https://python-docx.readthedocs.io/en/latest/) (can create / format word documents inside python).

1. Follow the instalation instructions, which say we can install python-docx using the following terminal command:
    ```terminal
    pip install python-docx 
    ```
1. In order to use the module in python, we can just refer to the name of the module (docx).
    ```python
    import docx

    docx._______
    ```
>Note: External python modules are generally stored in Lib folder. In PyCharm, go to External Libraries > lib > site-packages and there should be two new folders (docx and python_docx-0.8.6-py3.6.egg-info) 

\
\
**How to uninstall third party modules:**
1. Use the terminal command:
    ```terminal
    pip uninstall python-docx
    ```
___
### **Classes and Objects**

* Some data types dont fit into the standard categories (i.e. strings, numbers and boolians).
* We can use classes to define our own data types.

\
**Step 1:** Define a student _class_

_Student.py_
```python
class Student:

    def __init__(self, name, major, gpa, is_on_probation):
         self.name = name
         self.major = major
         self.gpa = gpa
         self.is_on_probation = is_on_probation
```
>Note: The initialize function establishes what attributes a student should have 

\
**Step 2:** Create a student or _object_ 

_app.py_
```python
from Student import Student

student1 = Student("Jim", "Business", 3.1, false)

student2 = Student("Pam", "Art", 2.5, true)
 
print(student1.name)   
```
>Note: We can access each of the attributes from this object (name, major, etc.)

>Summary: In Student.py we created a student data type, and in app.py we created student objects.
___
### **Building a Multiple Choice Quiz**

 **Step 1:** Create a question class to keep track of both the questions and answers

 _Question.py_
 ```python
class Question:
    def __init__(self, prompt, answer):
        self.prompt = prompt
        self.answer = answer
 ```
\
**Step 2:** Create question objects to use in conjunction with for loops to run simulation

_app.py_
```python
from Question import Question

question_prompts = [
    "What color are apples?\n(a) Red/Green\n(b) Purple\n(c) Orange\n\n",
    "What color are bananas?\n(a) Teal\n(b) Magenta\n(c) Yellow\n\n",
    "What color are strawberries?\n(a) Yellow\n(b) Red\n(c) Blue\n\n"
]

questions = [
    Question(question_prompts[0], "a"),
    Question(question_prompts[1], "c"),
    Question(question_prompts[2], "b")
]

def run_test(questions):
    score = 0
    for question in questions:
        answer = input(question.prompt)
        if answer == question.answer:
            score += 1
    print("You got" + str(score) + "/" + str(len(questions)) + "correct")

run_test(questions)
``` 
___
### **Object Functions**

* Functions that can be used inside of a class, to modify or provide specific information about objects in that class.

\
**Example 1:** Create a function inside a class to check if a student made honor roll

_Student.py_
```python
class Student:

    def __init__(self, name, major, gpa):
         self.name = name
         self.major = major
         self.gpa = gpa
    
    def on_honor_roll(self):
        if self.gpa >= 3.5:
            return True
        else:
            return False
```
_app.py_
```python
from Student import Student

student1 = Student("Oscar", "Accounting", 3.1)

student2 = Student("Phyllis", "Business", 3.8)
 
print(student1.on_honor_roll())   
```
___
### **Inheritance**

\
**Example 1:** Inherit functionality from an existing class into a new class.

_Chef.py_
```python
class Chef:

    def make_chicken(self):
        print("The chef makes a chicken")

    def make_salad(self):
        print("The chef makes a salad")
    
    def make_special_dish(self):
        print("The chef makes bbq ribs")
```

 _ChineseChef.py_
```python
from Chef import Chef
class ChineseChef(chef):
    
    def make_special_dish(self):
        print("The chef makes orange chicken")

    def make_fried_rice(self):
        print("The chef makes fried rice")
```

_app.py_
```python
from Chef import Chef
from ChineseChef import ChineseChef

myChef = Chef()
myChef.make_special_dish()

myChineseChef = ChineseChef()
myChinese Chef.make_special_dish()
myChinese Chef.make_chicken()
```
>Note: We define the special dish in _ChineseChef.py_ to override the function we inherited from _Chef.py_.
___
### **Python Interpreter**

* Environment in terminal where we can test out different python commands and functions in a safe and neutral environment.

* To access the python interpreter, open command prompt or terminal and type python3 and hit enter.
___
