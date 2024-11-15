# 📟 Data Types

#### Basic Data Types in Python

Python has several fundamental data types, each serving to represent different kinds of data. Here’s a quick overview:

* **Integer (int):** Represents whole numbers. Examples: `1`, `-5`, `1000`.
* **Float:** Represents decimal or fractional numbers. Examples: `3.14`, `-0.5`.
* **String (str):** Represents text or sequences of characters. Examples: `"Hello"`, `'Python'`, `"123"`.
* **Boolean (bool):** Represents logical values, either `True` or `False`.
* **List:** Used to store multiple values in an ordered sequence. Can contain different data types.
* **Tuple:** Similar to a list, but immutable (values cannot be changed). Often used to store fixed data.
* **Dictionary (dict):** Stores data in key-value pairs. Keys must be unique.
* **Set:** Used to store unique, unordered values, with support for set operations like unions and intersections.
* **Array:** Stores numeric data in multi-dimensional arrays (requires NumPy library).

These fundamental types are the most common and basic data types in Python. With Python’s flexible structure, you can combine these types to create more complex structures.

In Python programming, various data types are used to represent different data forms. Data types play an important role in determining how data is stored and processed by the program.

To start, let’s explore some of these basic data types.

**1. Numeric Data Types**

**a. Integer (int)**

Integers represent whole numbers without any decimal. Example:

```python
age = 25
student_count = 100
```

**b. Float**

Floats represent numbers with a fractional part. Example:

```python
pi = 3.14
price = 19.99
```

**2. Textual Data Type**

**String (str)**

The string data type represents text or sequences of characters. Strings can be defined using single (`'`) or double (`"`) quotes. Example:

```python
name = "Ahmet"
surname = 'Yilmaz'
```

**3. Boolean Data Type**

**Boolean (bool)**

The Boolean data type represents `True` or `False` values. It’s often used in conditional statements and decision-making structures. Example:

```python
is_true = True
is_false = False
```

These are the most basic data types in Python programming. However, there are more complex data types, such as:

* **Lists:** Used to store multiple values in an ordered sequence.
* **Tuples:** Similar to lists, but immutable.
* **Dictionaries:** Store data in key-value pairs.
* **Sets:** Used to store unique, unordered values.

You can refer to Python documentation or other resources for more detailed information on these complex data types.

**Checking Data Type with `type()`**

To check the data type of a variable or value, you can use the `type()` function, which returns the type of the object. Here’s how it works:

```python
x = 5
print(type(x))  # Output: <class 'int'>

name = "Ahmet"
print(type(name))  # Output: <class 'str'>

pi = 3.14
print(type(pi))  # Output: <class 'float'>

is_true = True
print(type(is_true))  # Output: <class 'bool'>
```

In this example, the `type()` function indicates that `x` is an integer (`int`), `name` is a string (`str`), etc. This allows you to identify the type of data you’re working with as you build your programs.

#### List of Data Types for Variable Assignments in Python

To change a variable's data type in Python, you can use type conversion functions to transform a value into a different data type. Here are some examples:

*   **Convert to Integer (`int`):**

    ```python
    number = "123"
    number_int = int(number)
    print(number_int)  # Output: 123
    ```
*   **Convert to Float:**

    ```python
    decimal_number = "3.14"
    decimal_number_float = float(decimal_number)
    print(decimal_number_float)  # Output: 3.14
    ```
*   **Convert to String (`str`):**

    ```python
    number = 123
    number_str = str(number)
    print(number_str)  # Output: "123"
    ```
*   **Convert to Boolean (`bool`):**

    ```python
    number = 0
    number_bool = bool(number)
    print(number_bool)  # Output: False
    ```

It’s important to perform conversion operations while ensuring compatibility between data types. For example, you can convert a string containing only numbers into an integer, but if the string contains letters, the conversion will result in an error.

{% embed url="https://www.youtube.com/watch?v=gCCVsvgR2KU" %}

{% embed url="https://www.youtube.com/watch?v=ppsCxnNm-JI" %}
