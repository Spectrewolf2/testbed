# Python Terms for Beginners

This guide introduces essential Python concepts with a brief description, example syntax, and the symbols or keywords that represent each concept.

---

## 1. Variable
- **Description:** A variable is a named container used to store data values.
- **Example Syntax:**
  ```python
  x = 10
  ```
- **Symbols/Keywords:** `=` (assignment operator)

## 2. Data Types

### Integer
- **Description:** Represents whole numbers without a fractional component.
- **Example Syntax:**
  ```python
  count = 42
  ```
- **Symbols/Keywords:** Numeric literals without a decimal point.

### Float
- **Description:** Represents real numbers that include decimals.
- **Example Syntax:**
  ```python
  pi = 3.14159
  ```
- **Symbols/Keywords:** Numeric literals with a decimal point.

### String
- **Description:** Represents sequences of characters (text) enclosed in quotes.
- **Example Syntax:**
  ```python
  name = "Alice"
  ```
- **Symbols/Keywords:** Quotes (`"` or `'`)

### Boolean
- **Description:** Represents one of two values: True or False.
- **Example Syntax:**
  ```python
  is_valid = True
  ```
- **Symbols/Keywords:** `True`, `False`

## 3. Operators

### Arithmetic Operators
- **Description:** Used for performing mathematical operations.
- **Example Syntax & Symbols:**
  - Addition:
    ```python
    3 + 2  # +
    ```
  - Subtraction:
    ```python
    5 - 2  # -
    ```
  - Multiplication:
    ```python
    3 * 4  # *
    ```
  - Division:
    ```python
    10 / 2  # /
    ```
  - Floor Division:
    ```python
    10 // 3  # //
    ```
  - Modulus:
    ```python
    10 % 3  # %
    ```
  - Exponentiation:
    ```python
    2 ** 3  # **
    ```

### Comparison Operators
- **Description:** Used to compare values.
- **Example Syntax & Symbols:**
  - Equal:
    ```python
    x == y  # ==
    ```
  - Not Equal:
    ```python
    x != y  # !=
    ```
  - Greater Than:
    ```python
    x > y  # >
    ```
  - Less Than:
    ```python
    x < y  # <
    ```
  - Greater or Equal:
    ```python
    x >= y  # >=
    ```
  - Less or Equal:
    ```python
    x <= y  # <=
    ```

### Logical Operators
- **Description:** Used to combine conditional statements.
- **Example Syntax & Symbols:**
  - And:
    ```python
    (x > 0) and (y > 0)  # and
    ```
  - Or:
    ```python
    (x > 0) or (y > 0)   # or
    ```
  - Not:
    ```python
    not(x == y)         # not
    ```

## 4. Functions
- **Description:** Blocks of reusable code designed to perform a specific task.
- **Example Syntax:**
  ```python
  def greet(name):
      return f"Hello, {name}!"
  ```
- **Symbols/Keywords:** `def`, `()`, `:`

## 5. Conditional Statements
- **Description:** Used to perform different computations or actions depending on whether a condition is true or false.
- **Example Syntax:**
  ```python
  if x > 0:
      print("Positive")
  elif x == 0:
      print("Zero")
  else:
      print("Negative")
  ```
- **Symbols/Keywords:** `if`, `elif`, `else`, `:`, indentation

## 6. Loops

### For Loop
- **Description:** Iterates over a sequence (such as a list, tuple, or string).
- **Example Syntax:**
  ```python
  for i in range(5):
      print(i)
  ```
- **Symbols/Keywords:** `for`, `in`, `range()`, `:`

### While Loop
- **Description:** Repeats a block of code as long as a condition is true.
- **Example Syntax:**
  ```python
  x = 0
  while x < 5:
      print(x)
      x += 1
  ```
- **Symbols/Keywords:** `while`, `:`, indentation

## 7. Collections

### List
- **Description:** An ordered, mutable collection of items.
- **Example Syntax:**
  ```python
  fruits = ["apple", "banana", "cherry"]
  ```
- **Symbols/Keywords:** Square brackets `[]`, commas `,`

### Tuple
- **Description:** An ordered, immutable collection of items.
- **Example Syntax:**
  ```python
  coordinates = (10, 20)
  ```
- **Symbols/Keywords:** Parentheses `()`, commas `,`

### Dictionary
- **Description:** A collection of key-value pairs.
- **Example Syntax:**
  ```python
  student = {"name": "Alice", "age": 21}
  ```
- **Symbols/Keywords:** Curly braces `{}`, colon `:`, commas `,`

### Set
- **Description:** An unordered collection of unique items.
- **Example Syntax:**
  ```python
  unique_numbers = {1, 2, 3}
  ```
- **Symbols/Keywords:** Curly braces `{}`, commas `,`

## 8. Classes and Objects
- **Description:**
  - Class: Defines a blueprint for objects.
  - Object: An instance of a class.
- **Example Syntax:**
  ```python
  class Dog:
      def __init__(self, name):
          self.name = name

      def bark(self):
          return "Woof!"

  my_dog = Dog("Buddy")
  print(my_dog.bark())
  ```
- **Symbols/Keywords:** `class`, `def`, `self`, `()`, `:`

## 9. Modules and Imports

### Modules
- **Description:** Files containing Python code (functions, classes, etc.) that can be imported into other Python programs.
- **Example Syntax:**
  ```python
  import math
  print(math.sqrt(16))
  ```
- **Symbols/Keywords:** `import`, dot `.` for accessing module members

## 10. Exception Handling
- **Description:** A way to gracefully handle errors using try and except blocks.
- **Example Syntax:**
  ```python
  try:
      result = 10 / 0
  except ZeroDivisionError:
      print("Cannot divide by zero!")
  ```
- **Symbols/Keywords:** `try`, `except`, `:`

## 11. Comments
- **Description:** Non-executable text that explains the code.
- **Example Syntax:**
  ```python
  # This is a single-line comment

  """
  This is a multi-line comment or docstring.
  It can span multiple lines.
  """
  ```
- **Symbols/Keywords:** `#` for single-line comments, triple quotes (`'''` or `"""`) for multi-line comments

## 12. Indentation
- **Description:** Python uses whitespace (indentation) to define blocks of code.
- **Example Syntax:**
  ```python
  if x > 0:
      print("x is positive")
  ```
- **Symbols/Keywords:** Indentation (typically 4 spaces) is used instead of braces `{}`
