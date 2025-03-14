# title


docstrings
type hints
methods
functions
variables
Data types:
- Numerical (integerts, floats, complex)
- strings ( indexing, slicing, negative indexing) immutable
- boolean
- set
- dictionary
- tuple
- list
- range
- boolean
  
-  Sequence (list, tuple, string)

-  variables: duck typing, named variables, boolean, dictionary, collection

-  -nested data structures- lists in lists, lists in dictionaries, dictionaries in dictionaries
-  -casting (convert data; explicit, implicit

-  -operators: arithmetic, assignment, bitwise, comparison/relational, identity, logical
-  -logical operator: and, or, not
-  bitwise operator: and '&', OR '|', NOT '~', XOR '^', binary right shift '>>', binary left shift '<<'

-  -values
-  order of operations

# Python Essential Concepts

This guide provides an overview of important Python concepts, including data types, operators, methods, functions, variables, and more.

---

## 1. Docstrings
- **Description:** Multi-line strings used to document modules, classes, functions, and methods.
- **Example Syntax:**
  ```python
  def greet(name):
      """
      This function returns a greeting message.
      :param name: Name of the person
      :return: Greeting string
      """
      return f"Hello, {name}!"
  ```
- **Symbols/Keywords:** `"""` (triple quotes)

## 2. Type Hints
- **Description:** Optional annotations to specify expected data types for function arguments and return values.
- **Example Syntax:**
  ```python
  def add(x: int, y: int) -> int:
      return x + y
  ```
- **Symbols/Keywords:** `:` for argument types, `->` for return types

## 3. Methods
- **Description:** Functions defined inside a class that operate on instances of the class.
- **Example Syntax:**
  ```python
  class Dog:
      def __init__(self, name: str):
          self.name = name

      def bark(self) -> str:
          return "Woof!"
  ```
- **Symbols/Keywords:** `self`, `def`, `()`, `:`

## 4. Functions
- **Description:** Blocks of reusable code designed to perform a specific task.
- **Example Syntax:**
  ```python
  def multiply(a, b):
      return a * b
  ```
- **Symbols/Keywords:** `def`, `()`, `return`, `:`

## 5. Variables
- **Description:** Named containers for storing values.
- **Example Syntax:**
  ```python
  x = 42
  name = "Alice"
  ```
- **Symbols/Keywords:** `=` (assignment operator)

### Duck Typing
- **Description:** Python determines the type of a variable at runtime.
- **Example Syntax:**
  ```python
  x = "hello"  # x is a string
  x = 10       # Now x is an integer
  ```
- **Symbols/Keywords:** No explicit type declaration

## 6. Data Types

### Numerical Types
- **Integer:** Whole numbers
  ```python
  x = 10
  ```
- **Float:** Decimal numbers
  ```python
  y = 3.14
  ```
- **Complex:** Numbers with a real and imaginary part
  ```python
  z = 2 + 3j
  ```

### String (Immutable)
- **Description:** A sequence of characters.
- **Example Syntax:**
  ```python
  s = "Hello, World!"
  
  # Indexing:
  print(s[0])  # 'H'
  
  # Negative Indexing:
  print(s[-1])  # '!'
  
  # Slicing:
  print(s[0:5])  # 'Hello'
  ```

### Boolean
- **Description:** Represents True or False.
- **Example Syntax:**
  ```python
  is_valid = True
  ```

### Set
- **Description:** Unordered collection of unique items.
- **Example Syntax:**
  ```python
  numbers = {1, 2, 3, 4, 5}
  ```

### Dictionary
- **Description:** Collection of key-value pairs.
- **Example Syntax:**
  ```python
  person = {"name": "Alice", "age": 25}
  ```

### Tuple (Immutable)
- **Description:** Ordered, immutable sequence of elements.
- **Example Syntax:**
  ```python
  coordinates = (10, 20)
  ```

### List
- **Description:** Ordered, mutable sequence of elements.
- **Example Syntax:**
  ```python
  fruits = ["apple", "banana", "cherry"]
  ```

### Range
- **Description:** Represents a sequence of numbers.
- **Example Syntax:**
  ```python
  numbers = range(5)  # 0, 1, 2, 3, 4
  ```

## 7. Sequences
- **Description:** Ordered collections of elements.
- **Examples:**
  ```python
  my_list = [1, 2, 3]   # List
  my_tuple = (1, 2, 3)  # Tuple
  my_string = "abc"     # String
  ```

## 8. Nested Data Structures
- **Description:** Data structures inside other data structures.
- **Examples:**
  ```python
  nested_list = [[1, 2, 3], [4, 5, 6]]
  dict_in_list = [{"name": "Alice"}, {"name": "Bob"}]
  nested_dict = {"user": {"name": "Alice", "age": 25}}
  ```

## 9. Casting (Type Conversion)

### Explicit Casting
- **Description:** Converting data types manually.
- **Example Syntax:**
  ```python
  x = int("10")  # Converts string to integer
  y = str(100)   # Converts integer to string
  ```

### Implicit Casting
- **Description:** Python automatically converts types.
- **Example Syntax:**
  ```python
  result = 5 + 2.0  # 7.0 (integer automatically converted to float)
  ```

## 10. Operators

### Arithmetic Operators
- Addition (`+`), Subtraction (`-`), Multiplication (`*`), Division (`/`)
- Floor Division (`//`), Modulus (`%`), Exponentiation (`**`)
- **Example Syntax:**
  ```python
  a = 10 + 5  # 15
  b = 10 % 3  # 1
  c = 2 ** 3  # 8
  ```

### Assignment Operators
- **Example Syntax:**
  ```python
  x = 5
  x += 2  # x = x + 2
  ```

### Comparison (Relational) Operators
- **Example Syntax:**
  ```python
  5 == 5  # True
  10 != 5  # True
  ```

### Logical Operators
- **Example Syntax:**
  ```python
  (x > 0) and (y > 0)
  ```

### Bitwise Operators
- AND (`&`), OR (`|`), NOT (`~`), XOR (`^`)
- Binary Right Shift (`>>`), Binary Left Shift (`<<`)
- **Example Syntax:**
  ```python
  a = 5 & 3   # 1
  b = 5 | 3   # 7
  c = 5 ^ 3   # 6
  d = ~5      # -6
  e = 5 >> 1  # 2
  f = 5 << 1  # 10
  ```

## 11. Values
- **Description:** Data stored in variables.
- **Examples:**
  ```python
  x = 42
  y = "hello"
  ```

## 12. Order of Operations
- **Description:** Python follows the standard PEMDAS order:
  - Parentheses `()`
  - Exponents `**`
  - Multiplication `*`, Division `/`, Floor Division `//`, Modulus `%`
  - Addition `+`, Subtraction `-`
  - Comparison, Logical, Bitwise operations
- **Example Syntax:**
  ```python
  result = (2 + 3) * 4  # 20
  ```
