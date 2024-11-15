# 🚀Variables

### Basic Concepts of Variables in Python

Variables are fundamental building blocks used to store and process data. Defining variables in Python is straightforward. To create a variable, simply choose a name and assign a value to it. Here’s the basic usage:

```python
# Defining variables and assigning values
name = "Ahmet"
age = 25
pi = 3.14
```

In the example above, `name`, `age`, and `pi` are assigned a text, an integer, and a floating-point number, respectively.

#### Properties of Variables in Python

1. **Variable Names**

When naming variables in Python, there are a few rules to follow. These rules help keep your code more readable and error-free. Here are the basic rules for naming variables in Python:

* Variable names must start with a letter (A-Z or a-z) or an underscore (\_). They cannot start with a number.
* Names can contain letters (A-Z or a-z), digits (0-9), or underscores (\_).
* Python is case-sensitive, meaning `name` and `Name` would be considered different variables.
* Reserved keywords in Python (such as `if`, `else`, `while`, `for`, `def`, etc.) cannot be used as variable names.
* Variable names should be meaningful and descriptive to help other developers understand your code better.
* Names cannot contain spaces or special characters. Only letters, numbers, and underscores are allowed.
* For longer variable names, use naming styles like `snake_case` or `camelCase`:
  * `snake_case` separates words with underscores, all lowercase.
  * `camelCase` uses lowercase for the first word and capitalizes subsequent words.

Examples:

```python
# Valid variable names
name = "Ahmet"
age = 25
average_grade = 85.5
total_people = 100

# Invalid variable names
5_years = 5  # Cannot start with a digit
if = 10      # Cannot use a reserved keyword
first name = "Ali Veli"  # Cannot contain spaces
```

By following these rules when creating variable names, you ensure your code is more readable and understandable.

2. **Reserved Keywords in Python**

Python’s reserved keywords have special meanings and serve specific functions in the language. These keywords define the syntax and semantics of Python, so they cannot be used as variable names. Here are Python's reserved keywords:

```python
False, class, finally, is, return
None, continue, for, lambda, try
True, def, from, nonlocal, while
and, del, global, not, with
as, elif, if, or, yield
assert, else, import, pass
break, except, in, raise
```

#### Multi-Word Variable Names

In Python, there are different approaches to creating variable names that consist of multiple words:

*   **Snake Case:** In this style, all letters are lowercase, and words are separated by underscores.

    ```python
    average_grade = 85.5
    student_full_name = "Ahmet Yılmaz"
    ```
*   **Camel Case:** In this style, the first word is lowercase, and subsequent words start with a capital letter.

    ```python
    averageGrade = 85.5
    studentFullName = "Ahmet Yılmaz"
    ```

Both approaches are valid, but "snake\_case" is more commonly used in the Python community, as it aligns with Python libraries and standards. Regardless of the style you choose, variable names should be meaningful, descriptive, and helpful to other developers reading your code.

3. **Variable Types**

In Python, the type of a variable is automatically determined when a value is assigned. You don't need to specify the type. Basic data types include:

* `int` (integer)
* `float` (floating-point number)
* `str` (string)
* `bool` (boolean - `True` or `False`)

Example:

```python
age = 25              # int
average_grade = 85.5  # float
name = "Ahmet"        # str
is_correct = True     # bool
```

#### Using Variables

**Assigning Values to Variables**

Assigning a value to a variable in Python is simple. After defining a variable, you can assign any value to it. Here are some examples:

**Assigning an Integer:**

```python
x = 10
```

**Assigning a Floating-Point Number:**

```python
pi = 3.14
```

**Assigning a String:**

```python
name = "Ahmet"
```

**Assigning a Boolean Value:**

```python
is_correct = True
```

**Assigning Values from Other Variables:**

```python
x = 5
y = x  # Assigns the value of x to y
```

**Assigning Results of Expressions:**

```python
a = 5
b = 10
total = a + b  # Assigns the result of the expression to total
```

**Swapping Values:**

```python
x = 5
y = 10

x, y = y, x  # Swaps the values of x and y
```

As shown in these examples, once a variable is defined, you can directly assign a value to it. Since Python is a dynamically typed language, you don’t need to specify the type of the variable beforehand; Python will determine it based on the assigned value.

**Reassigning Values to Variables**

In Python, it’s easy to change the value of a variable by reassigning it. To update a variable’s value, simply reassign it:

```python
x = 5
print("Initial value of x:", x)

x = 10  # Updates the value of x
print("Updated value of x:", x)

y = 2
y = y + 3  # Updates the value of y (new value: 5)
print("Updated value of y:", y)

z = 7
z += 1  # Increases z by 1 (new value: 8)
print("Updated value of z:", z)
```

As seen above, reassigning a variable is as simple as assigning it a new value. You can also use shorthand operators (like `+=` or `-=`) to increase or decrease a variable’s value.

**Swapping Values of Multiple Variables in One Line**

Python allows you to assign values to multiple variables simultaneously on a single line:

```python
x = 10
y = 5
x, y = y, x  # Swaps values of x and y
```

This approach allows you to match multiple variables with corresponding values in a single statement. Be sure the number of variables matches the number of values; otherwise, you’ll get an error.

**Assigning Values to Multiple Variables in One Line**

Python also enables assigning values to multiple variables on a single line:

```python
a, b, c = 5, 3.2, "Hello"

print(a)
print(b)
print(c)
```

Output:

```
5
3.2
Hello
```

Note: Ensure the number of variables matches the number of values; otherwise, you’ll encounter an error.

**Assigning the Same Value to Multiple Variables**

If you want to assign the same value to multiple variables at once, you can do it like this:

```python
x = y = z = "same"

print(x)
print(y)
print(z)
```

Output:

```
same
same
same
```

In this example, the string `"same"` is assigned to all three variables, `x`, `y`, and `z`.

You can also perform mathematical operations using variables:

```python
a = 10
b = 5
sum_result = a + b
product = a * b
division = a / b
```

With this foundational information, you can create more detailed guides in GitBook about working with variables in Python. As you progress, you can delve into more advanced topics like data structures, conditions, loops, and functions.

{% embed url="https://www.youtube.com/watch?v=cQT33yu9pY8" %}
