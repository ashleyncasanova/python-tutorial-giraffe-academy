## [**Python Tutorial**](https://www.youtube.com/watch?v=rfscVS0vtbw&t=2078s)
____
### **Intro:**

* _Python_ is a programing language.
* Need a _text editor_ to write code in (notepad, text edit, etc.)
>Note: There are special text editors for writing python code called IDE's (integrated develepment environments), we will use _PyCharm_.
____
### **Variables:**
* A _variable_ is a container where we can store certain data types.
    ```
    variable_name = "some value"
    ```
____
### **Data Types:**

* **Strings** - Store text. Must be written in quotations.
    ```
    character_name = "Tom"
    ```
* **Numbers** - Store whole or decimal numbers. 
    ```
    character_age = 50
    ```
* **Boolians** - Store True or False value.
    ```
    is_male = True
    ```
>Note: Can adjust data types in middle of code.
____
### **Working With Strings:**

* **Example:** A backslash is called the escape character; meaning that whatever character comes after it we want to render literally.

    ```python
    print("Giraffe Academy")
    ```
    >Giraffe Academy

    ```python
    print("Giraffe\"Academy")
    ```
    >Giraffe"Academy

    ```python
    print("Giraffe\Academy")
    ```
    >Giraffe\Academy
    ```python
    print("Giraffe\nAcademy")
    ```
    >Giraffe  
    Academy

* **Example:** We can store this string value inside of a variable
    ```python
    phrase = "Giraffe Academy"
    print(phrase)
    ```
    >Giraffe Academy

* **Example:** Concatination is the process of joining strings together.
    ```python
    phrase = "Giraffe Academy"
    print(phrase + "is cool")
    ```
    >Giraffe Academy is cool

**Example:** We can use functions to modify, or get information, about our strings.
1. The function .lower() will convert the entire string to lower case.
    ```python
    phrase = "Giraffe Academy"
    print(phrase.lower())
    ```
    >giraffe academy
2. The function .upper() will convert the entire string to upper case.
    ```python
    phrase = "Giraffe Academy"
    print(phrase.upper())
    ```
    >GIRAFFE ACADEMY
3. The function .islower() will check if the phrase is lower case and return a T/F value.
    ```python
    phrase = "Giraffe Academy"
    print(phrase.islower())
    ```
    >False
    ```python
    phrase = "Giraffe Academy"
    print(phrase.isupper())
    ```
    >False
    ```python
    phrase = "Giraffe Academy"
    print(phrase[0])
    ```
    >g
____

r