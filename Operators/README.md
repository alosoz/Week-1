# 🕰️ Operators

## Python Operators

Operators in Python are symbols or special words used to manipulate different types of data, perform calculations, or compare values. Operators are one of the fundamental building blocks of programming, and Python offers a wide range of them. Here are some commonly used types of operators in Python:

### 1. Arithmetic Operators

Arithmetic operators are used for mathematical calculations:

* `+`: Addition
* `-`: Subtraction
* `*`: Multiplication
* `/`: Division
* `%`: Modulus (finding the remainder)
* `**`: Exponentiation

**Example:**

```python
x = 10
y = 3

total = x + y
difference = x - y
product = x * y
quotient = x / y
remainder = x % y
power = x ** y
```

```python
x = 15
y = 4

# Output: x + y = 19
print('x + y =', x + y)

# Output: x - y = 11
print('x - y =', x - y)

# Output: x * y = 60
print('x * y =', x * y)

# Output: x / y = 3.75
print('x / y =', x / y)

# Output: x // y = 3
print('x // y =', x // y)

# Output: x ** y = 50625
print('x ** y =', x ** y)
```

### 2. Comparison Operators

Comparison operators are used to compare values and create conditions:

* `==`: Equal to?
* `!=`: Not equal to?
* `<`: Less than?
* `>`: Greater than?
* `<=`: Less than or equal to?
* `>=`: Greater than or equal to?

**Example:**

```python
x = 5
y = 7

is_equal = x == y
is_less = x < y
is_greater = x > y
```

```python
x = 10
y = 12

# Output: x > y is False
print('x > y is', x > y)

# Output: x < y is True
print('x < y is', x < y)

# Output: x == y is False
print('x == y is', x == y)

# Output: x != y is True
print('x != y is', x != y)

# Output: x >= y is False
print('x >= y is', x >= y)

# Output: x <= y is True
print('x <= y is', x <= y)
```

### 3. Logical Operators

Logical operators are used to manipulate logical values (True or False):

* `and`: Logical AND
* `or`: Logical OR
* `not`: Logical NOT

**Example:**

```python
a = True
b = False

result1 = a and b
result2 = a or b
result3 = not a
```

```python
x = True
y = False

print('x and y is', x and y)

print('x or y is', x or y)

print('not x is', not x)
```

In Python, `and` and `or` are logical operators that perform logical operations. These operators are typically used when combining conditions or evaluating comparison expressions. Here’s how `and` and `or` differ:

*   **`and` Operator**: This operator results in `True` only when both conditions are `True`. That is, all conditions must be true.

    **Example:**

    ```python
    x = 5
    y = 10
    if x > 0 and y > 0:
        print("Both conditions are true.")
    ```
*   **`or` Operator**: This operator results in `True` if at least one condition is `True`. That is, at least one condition must be true.

    **Example:**

    ```python
    x = 5
    y = -2
    if x > 0 or y > 0:
        print("At least one condition is true.")
    ```

In summary, the `and` operator results in `True` when all conditions are true, while the `or` operator results in `True` when at least one condition is true. These operators are quite useful for combining conditional statements and making logical decisions.

### 4. Assignment Operators

Assignment operators are used to assign values to variables:

* `=`: Value assignment
* `+=`: Add and assign
* `-=`: Subtract and assign
* `*=`: Multiply and assign
* `/=`: Divide and assign
* `%=`: Modulus and assign
* `**=`: Exponentiate and assign

**Example:**

```python
x = 10
y = 3

x += y  # x = x + y
x -= y  # x = x - y
x *= y  # x = x * y
x /= y  # x = x / y
x %= y  # x = x % y
x **= y  # x = x ** y
```

These examples demonstrate the basic Python operators. Operators are powerful tools that form the foundation of programming, and with more complex operators and expressions, you can create advanced programs.

{% embed url="https://www.youtube.com/watch?v=v5MR5JnKcZI&ab_channel=Telusko" %}
