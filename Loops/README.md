# 📺 Loops

## Loops in Python

Loops are an important structure used to repeat a specific operation. Below are different types of loops and examples explaining their usage:

### 1. For Loop

The `for` loop is used to iterate over a specific list, array, or iterable data structure.

#### Example 1: Printing List Elements

```python
colors = ["red", "blue", "green", "yellow"]

for color in colors:
    print(color)
```

#### Example 2: Summing Numbers

```python
numbers = [1, 2, 3, 4, 5]
total = 0

for num in numbers:
    total += num

print("Total:", total)
```

### 2. While Loop

The `while` loop is used to repeat an operation as long as a certain condition is true.

#### Example 3: Number Guessing Game

```python
import random

target_number = random.randint(1, 100)
guess = None

while guess != target_number:
    guess = int(input("Enter your guess: "))
    if guess < target_number:
        print("Guess a higher number.")
    elif guess > target_number:
        print("Guess a lower number.")
    else:
        print("Congratulations! Your guess is correct:", target_number)
```

#### Example 4: Calculating Factorial

```python
number = int(input("Enter a number to calculate its factorial: "))
factorial = 1
i = 1

while i <= number:
    factorial *= i
    i += 1

print(f"The factorial of {number} is:", factorial)
```

Loops are essential tools for repeating specific tasks and processing data. The examples demonstrate how to use `for` and `while` loops in different scenarios.

### Nested Loops

Nested loops mean using one loop inside another. These types of loops are useful for creating more complex structures and processing data more deeply. Here are explanations and examples of nested loops:

#### Nested For Loops

**Example 1: Multiplication Table**

```python
for i in range(1, 6):
    for j in range(1, 6):
        print(i * j, end="\t")
    print()
```

In this example, we create a multiplication table for numbers from 1 to 5. We use two nested `for` loops to print each multiplication result.

#### Nested While Loops

**Example 2: Star Triangle**

```python
size = 5
row = 1

while row <= size:
    col = 1
    while col <= row:
        print("*", end="")
        col += 1
    print()
    row += 1
```

In this example, we create a triangle pattern made of stars. We use two nested `while` loops to print the stars in the correct order.

#### Combined For and While Loops

**Example 3: Matrix Transposition**

<pre class="language-python"><code class="lang-python"><strong>matrix = [[1, 2, 3],
</strong>          [4, 5, 6],
          [7, 8, 9]]

transposed = []

for i in range(len(matrix[0])):
    row = []
    for j in range(len(matrix)):
        row.append(matrix[j][i])
    transposed.append(row)

for row in transposed:
    print(row)
</code></pre>

In this example, we calculate the transpose of a matrix. We use nested `for` loops to convert the columns of the matrix into rows.

Nested loops are useful for creating more complex patterns or processing data in more depth. However, understanding and managing such loops can be more complex, so they should be used carefully and logically.

### Infinite Loops

Infinite loops occur when a loop runs continuously without a certain condition to terminate it. These loops often result from programmer errors and can cause programs to hang unexpectedly. Let's examine an example of an infinite loop:

```python
while True:
    print("This loop is infinite!")
```

In the above example, the statement `while True:` creates an infinite loop. Since the condition is always true, the code inside will continuously run, and the program will never exit this loop. Such loops can cause the program to freeze.

To prevent infinite loops, it is important to correctly set loop conditions or use appropriate exit mechanisms within the loop. For example:

```python
while True:
    user_input = input("Press 'q' to exit: ")
    if user_input == 'q':
        break
    else:
        print("Invalid input.")
```

In this example, there is a loop that continues to take user input until the user presses "q". When the user presses "q", the loop is terminated using the `break` statement.

Avoiding infinite loops and controlling your loops logically is crucial for ensuring your program runs smoothly.

### For Loop Infinite Loop

In Python, a `for` loop is typically used to process elements in a sequential data structure one by one. However, if no condition is specified to terminate the loop, the `for` loop can become an infinite loop. This situation is referred to as a "for infinite loop."

#### Example of an Infinite For Loop

```python
for i in range(5):
    print("This loop is infinite!")
```

Here, we would normally expect a `for` loop that iterates from 0 to 4 using `range(5)`. However, since there is no exit condition or mechanism in the loop, this loop will run indefinitely.

To avoid making such mistakes, it is important to properly set the loop condition when using `for` loops and provide a mechanism to terminate the loop. For example:

```python
for i in range(5):
    user_input = input("Press 'q' to exit the loop: ")
    if user_input == 'q':
        break
    print(f"{i} process completed.")
```

In this case, the loop will terminate if the user presses "q". Otherwise, an operation is performed in each iteration.

Avoiding infinite loops in `for` loops and controlling your loops is crucial for ensuring your program runs correctly and as expected.

### Break and Continue Statements

The `break` and `continue` statements are two keywords used in Python to change the flow of control in loops. These statements affect the behavior of loops and are used to terminate or skip iterations under certain conditions.

#### Break Statement

The `break` statement is used to terminate a loop abruptly. If a specific condition is met, the loop ends immediately.

**Example 1: Number Guessing Game**

```python
target_number = 42

while True:
    guess = int(input("Enter your guess: "))
    if guess == target_number:
        print("Congratulations, correct guess!")
        break
    else:
        print("Wrong guess, try again.")
```

In this example, the infinite `while` loop is terminated using the `break` statement when the user makes a correct guess.

#### Continue Statement

The `continue` statement is used to skip certain iterations within a loop that meet a specific condition. When the condition is met, the remaining part of the loop is skipped, and control moves to the next iteration.

**Example 2: Printing Even Numbers**

```python
for i in range(1, 11):
    if i % 2 == 1:
        continue
    print(i, "is an even number.")
```

In this example, the `continue` statement is used to print only even numbers. Odd numbers are skipped, and the loop moves to the next iteration.

The `break` and `continue` statements are useful tools for controlling the flow within loops based on specific conditions. However, excessive use of these statements or creating complex flow in your code can make it harder to understand. Therefore, they should be used carefully.

{% embed url="https://www.youtube.com/watch?v=0ZvaDa8eT5s&ab_channel=Telusko" %}



{% embed url="https://www.youtube.com/watch?v=HZARImviDxg&ab_channel=Telusko" %}
