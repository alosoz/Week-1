# Page

## Strings in Python

A string is a data type used in computer programming that represents a sequence of characters. Strings are used to represent words, sentences, or any character sequences. They are an important data type in Python and many other programming languages, utilized in various fields such as text processing, data analysis, receiving user input, and reading/writing text-based files.

Strings are typically created by enclosing text in double quotes (`"..."`) or single quotes (`'...'`). Here are some examples:

```python
name = "Ahmet"
surname = 'Yılmaz'
sentence = "Hello, world!"
```

You can perform various operations with strings, such as:

#### Concatenation

You can concatenate strings:

```python
full_name = name + " " + surname  # "Ahmet Yılmaz"
```

#### Repetition

You can create repetitions by multiplying strings:

```python
repeated_text = name * 3  # "AhmetAhmetAhmet"
```

#### Length

You can measure the length of a string:

```python
length = len(sentence)  # Number of characters in 'sentence'
```

#### Searching

You can search for specific characters or substrings within strings:

```python
if "world" in sentence:
    print("The word 'world' is in the sentence.")
```

#### Slicing

You can slice strings:

```python
pythonKodu kopyalasubstring = sentence[8:13]  # "world"
```

You can use indices to access specific characters in a string or perform operations on it. Indices specify the order of characters in a string and start from zero. Positive indices increase from left to right (starting at 0), while negative indices increase from right to left (starting at -1).

For example, consider the word "Hello":

```diff
 H  e  l  l  o
 0  1  2  3  4
-5 -4 -3 -2 -1
```

This table shows the positive and negative indices for each character.

You can access a specific character or substring in a string using its index. Here are some examples:

```python
text = "Hello"

first_character = text[0]  # "H"
second_character = text[1]  # "e"
last_character = text[-1]  # "o"
```

You can also use indices in slicing operations:

```python
pythonKodu kopyalasubstring = text[1:4]  # "el"
```

This example retrieves a substring containing the characters from index 1 to 4 (not including 4).

#### String Slicing

In Python, when slicing a string, the starting index is included, while the ending index is not. For instance, consider the word "Hello":

```
 H  e  l  l  o
 0  1  2  3  4
```

If the variable `text` is "Hello":

* The slice `text[1:4]` contains characters starting from index 1 (`e`) to index 4 (not including `l`), resulting in "el".
* The slice `text[2:5]` contains characters starting from index 2 (`l`) to index 5 (not including `o`), resulting in "ll".

This behavior is due to indices starting from 0, and counting the characters between the indices indicates how many characters will be included in the slice. Thus, the starting index is included while the ending index is excluded.

If only the starting or ending index is omitted, Python automatically slices from the beginning or to the end of the string. For example:

* The expression `text[:4]` includes characters from the start of the string to index 4 (not including), resulting in "Hell".
* The expression `text[2:]` includes characters starting from index 2 (`l`) to the end of the string, resulting in "llo".
* The expression `text[:]` includes the entire string.

It's important to note that while the starting index is included, the ending index is not when performing slicing.

These are just basic examples of string manipulation. Python provides many functions and methods to perform more complex operations, format strings, and manipulate text.

#### String Methods in Python

Python has a variety of string methods for manipulating string data. These methods are used to process, transform, and format text data. Here are some commonly used Python string methods:

* `len()`: Returns the length of a string. Note: The `len` method starts from 1, which is different from indexing.

```python
text = "Hello, world!"
length = len(text)  # 13
```

* `lower()`: Converts the string to lowercase.

```python
text = "Hello, WORLD!"
lowercase = text.lower()  # "hello, world!"
```

* `upper()`: Converts the string to uppercase.

```python
text = "Hello, world!"
uppercase = text.upper()  # "HELLO, WORLD!"
```

* `capitalize()`: Capitalizes the first character of the string, leaving the rest in lowercase.

```python
text = "hello, world!"
capitalized = text.capitalize()  # "Hello, world!"
```

* `title()`: Capitalizes the first character of each word in the string.

```python
text = "hello, world!"
title_case = text.title()  # "Hello, World!"
```

* `strip()`: Removes whitespace from the beginning and end of the string.

```python
text = "   Hello, world!   "
cleaned_text = text.strip()  # "Hello, world!"
```

* `split()`: Splits the string by a specified delimiter and returns a list.

```python
text = "Hello,world,how are you?"
words = text.split(",")  # ["Hello", "world", "how are you?"]
```

* `replace()`: Replaces a specified substring with another substring.

```python
text = "Hello, world!"
new_text = text.replace("Hello", "Hi")  # "Hi, world!"
```

* `find()`: Returns the index of a specified substring in the string.

```python
text = "Hello, world!"
position = text.find("world")  # 7
```

* `startswith()`: Checks if the string starts with a specified substring.

```python
text = "Hello, world!"
if text.startswith("Hello"):
    print("It starts with 'Hello'!")
```

* `endswith()`: Checks if the string ends with a specified substring.

```python
text = "Hello, world!"
if text.endswith("world!"):
    print("It ends with 'world!'")
```

These are just a few examples, and there are many different string methods available in Python. Using string methods makes it easy to process and format text data. For more information on string methods, you can refer to the Python documentation.

{% embed url="https://www.youtube.com/watch?v=Ctqi5Y4X-jA" %}
