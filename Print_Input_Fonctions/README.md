# 💾Print-Input Fonctions

#### The `print()` Function

In Python, the `print()` function is used to output text or values to the console or output stream. This function is helpful for tracking the program’s execution, debugging, or interacting with the user. Here are some basic uses and examples of the `print()` function:

**Basic Usage:**

```python
print("Hello, world!")
```

**Using Variables with `print()`:**

```python
name = "Ahmet"
age = 25
print("Hello,", name, ". You are", age, "years old.")
```

**Printing Different Data Types:**

```python
number = 42
decimal_number = 3.14
text = "Python"
is_true = True

print("Integer:", number)
print("Float:", decimal_number)
print("String:", text)
print("Boolean:", is_true)
```

**Printing Outputs on the Same Line:**

```python
print("Hello,", end=" ")
print("world!")
```

**Printing Multiple Values Together:**

```python
name = "Ahmet"
age = 25
print("Hello,", name, ". You are", age, "years old.", sep="-")
```

As you can see, the `print()` function takes text and variables, separated by commas. By default, each `print()` call outputs on a new line. However, you can change this behavior using the `end` parameter. Additionally, with the `sep` parameter, you can specify the character to use as a separator between values.

The `print()` function is especially useful during development for viewing values and results. It’s a basic tool for debugging and understanding program flow.

**Parameters of the `print()` Function:**

*   **objects:** Refers to the objects (values or variables) to print. Multiple objects can be separated by commas. Example:

    ```python
    name = "Ahmet"
    age = 25
    print("My name is", name, "and I am", age, "years old.")
    # Output: My name is Ahmet and I am 25 years old.
    ```
*   **sep:** Specifies the separator character between objects. Example:

    ```python
    name = "Ahmet"
    surname = "Yilmaz"
    print(name, surname, sep="-")
    # Output: Ahmet-Yilmaz
    ```
*   **end:** Specifies the character used at the end of the `print()` output. Example:

    ```python
    print("Hello", end="!")  # Uses an exclamation mark instead of a newline at the end
    # Output: Hello!
    ```

**Escape Sequences**

Escape sequences are special character sequences in Python (and many other programming languages) used to insert special characters into strings, like newlines. The escape sequence , for instance, represents a "newline" character.

Example:

```python
print("Hello,\nworld!")
```

This code will produce a two-line output:

```
Hello,
world!
```

Using escape sequences like  can help you split text across multiple lines or create more organized outputs.

In these examples, I’ve shown different parameters and features of the `print()` function. You can use these parameters to customize your outputs and adapt to various scenarios.

***

#### Receiving Input

In Python, you can get input from the user using the `input()` function. This function waits for the user to enter text and returns the entered text as a string. Here’s how to use the `input()` function with examples:

**Basic Usage:**

```python
user_input = input("Please enter some text: ")
print("You entered:", user_input)
```

In this example, the user is prompted to enter text, which is then assigned to the variable `user_input`. The entered text is then displayed on the screen.

**Converting Input to a Number:**

```python
age = input("Enter your age: ")
age_int = int(age)
print("In the future, you will be", age_int + 10, "years old.")

# Alternative method:
age = int(input("Enter your age: "))
print("In the future, you will be", age + 10, "years old.")
```

After getting input from the user, you can convert the entered text to a number using the `int()` function if needed. In this example, after the user enters their age, the program calculates and prints their age in ten years.

**Converting Input to a Decimal:**

```python
height = input("Enter your height in meters: ")
height_float = float(height)
print("Double your height:", height_float * 2)
```

If you expect the user to enter a decimal number, you can use the `float()` function to convert the input text to a float.

When using `input()`, the program pauses until the user enters text and presses Enter. After receiving input, the program continues.

While receiving input, make sure to handle errors if the input type is unexpected. It’s essential to prevent program crashes or errors when the user enters something other than what you expect.

{% embed url="https://www.youtube.com/watch?v=DB9Cq6TSTuQ&ab_channel=BroCode" %}
