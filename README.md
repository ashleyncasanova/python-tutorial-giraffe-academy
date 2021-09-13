## [**Python Tutorial**](https://www.youtube.com/watch?v=rfscVS0vtbw&t=2078s)
____
### **Intro:**

* _Python_ is a programing language.
* Need a _text editor_ to write code in (notepad, text edit, etc.)
>Note: There are special text editors for writing python code called IDE's (integrated develepment environments), we will use _PyCharm_.
____
### **Variables:**
* A _variable_ is a container where we can store certain data types.
    ```python
    variable_name = "some value"
    ```
____
### **Data Types:**

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
### **Working With Strings:**
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
print (phrase_______)
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
>Note: Index numbers re assigned begining at 0 (i.e. G = 0, i = 1, r = 3, etc.)

\
**Example 5:** Functions can be used in combination with eachother.
```python
phrase = "Giraffe Academy"
print (phrase.upper().isupper())
```

>_Returns:_ True

\
**Example 6:** The length function will return the length of a string.
```python
phrase = "Giraffe Academy"
print (len(phrase))
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