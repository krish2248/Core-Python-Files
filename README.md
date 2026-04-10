# Core Python Files

A comprehensive Python learning repository containing structured lessons, practice notebooks, and coding exercises. This collection covers Python fundamentals through advanced concepts, designed for building a strong foundation in programming.

## Repository Structure

```
Core-Python-Files/
├── 1.ipynb - 13.ipynb    # Sequential lesson notebooks
├── Notes/                 # Detailed topic notes (HTML/PDF)
├── 50 Tasks Core Python/  # Practice exercises
├── Krish.py              # Python script examples
└── krish.txt             # Additional notes
```

## Curriculum Overview

### Lesson Notebooks (1-13)

| Notebook | Topics |
|----------|--------|
| `1.ipynb` | Python Introduction, Variables, Data Types |
| `2.ipynb` | Operators, Input/Output |
| `3.ipynb` | Lists - Creation, Indexing, Methods |
| `4.ipynb` | Tuples - Immutable Sequences |
| `5.ipynb` | Sets - Unique Collections, Operations |
| `6.ipynb` | Dictionaries - Key-Value Pairs |
| `7.ipynb` | Conditional Statements (if/elif/else) |
| `8.ipynb` | For Loops - Iteration Patterns |
| `9.ipynb` | While Loops - Conditional Iteration |
| `10.ipynb` | Functions - Definition, Parameters, Returns |
| `11.ipynb` | Lambda Functions - Anonymous Functions |
| `12.ipynb` | Date and Time Module |
| `13.ipynb` | Comprehensions - List, Dict, Set |

### Notes Directory

Detailed reference notes in HTML and PDF formats:

| Note | Content |
|------|---------|
| `1) Intro.html` | Python overview and setup |
| `2) introduction.html` | Language fundamentals |
| `3) List.html` | List operations and methods |
| `4) Tuple.html` | Tuple characteristics |
| `5) Set.html` | Set theory and operations |
| `6) Dict.html` | Dictionary manipulation |
| `7) If & Else.html` | Conditional logic |
| `8) For loop.html` | For loop patterns |
| `9) While Loop.html` | While loop applications |
| `10) Function.html` | Function design |
| `11) lambda function.html` | Lambda expressions |
| `12) Date and Time Module.html` | datetime module |
| `13) Comprehension.html` | Pythonic comprehensions |
| `14) Exception Handling.html` | try/except blocks |
| `15) Class & Object.html` | OOP fundamentals |
| `16) Encapsulation.html` | Data hiding |
| `17) Inheritance.html` | Class inheritance |

## Topics Covered

### Data Types and Structures

#### Primitive Types
```python
# Integer
age = 25

# Float
price = 19.99

# String
name = "Python"

# Boolean
is_valid = True
```

#### Collections
```python
# List - Ordered, Mutable
numbers = [1, 2, 3, 4, 5]

# Tuple - Ordered, Immutable
coordinates = (10, 20)

# Set - Unordered, Unique
unique_items = {1, 2, 3}

# Dictionary - Key-Value Pairs
person = {"name": "Krish", "age": 25}
```

### Control Flow

#### Conditionals
```python
if condition:
    # execute if true
elif another_condition:
    # execute if first false, this true
else:
    # execute if all false
```

#### Loops
```python
# For loop
for item in collection:
    process(item)

# While loop
while condition:
    execute()
```

### Functions

```python
# Standard function
def greet(name):
    return f"Hello, {name}!"

# Lambda function
square = lambda x: x ** 2

# Default parameters
def power(base, exponent=2):
    return base ** exponent
```

### Object-Oriented Programming

```python
class Animal:
    def __init__(self, name):
        self.name = name
    
    def speak(self):
        pass

class Dog(Animal):
    def speak(self):
        return f"{self.name} says Woof!"
```

### Exception Handling

```python
try:
    result = risky_operation()
except ValueError as e:
    handle_error(e)
finally:
    cleanup()
```

### Comprehensions

```python
# List comprehension
squares = [x**2 for x in range(10)]

# Dictionary comprehension
word_lengths = {word: len(word) for word in words}

# Set comprehension
unique_lengths = {len(word) for word in words}
```

## Practice Exercises

The `50 Tasks Core Python/` directory contains programming exercises covering:

1. Variable manipulation
2. String operations
3. List and dictionary tasks
4. Loop-based problems
5. Function implementations
6. File handling
7. Error handling scenarios
8. OOP exercises

## Learning Path

### Week 1-2: Fundamentals
- Notebooks 1-2: Introduction and data types
- Notes: Intro, Variables, Operators

### Week 3-4: Data Structures
- Notebooks 3-6: Lists, Tuples, Sets, Dictionaries
- Practice: Collection manipulation tasks

### Week 5-6: Control Flow
- Notebooks 7-9: Conditionals and Loops
- Practice: Logic and iteration problems

### Week 7-8: Functions
- Notebooks 10-11: Functions and Lambdas
- Practice: Function-based exercises

### Week 9-10: Advanced Topics
- Notebooks 12-13: Datetime, Comprehensions
- Notes: Exception Handling, OOP

### Week 11-12: OOP Mastery
- Notes 15-17: Classes, Encapsulation, Inheritance
- Practice: OOP design exercises

## Requirements

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Basic text editor for .py files

## Installation

```bash
git clone https://github.com/krish2248/Core-Python-Files.git
cd Core-Python-Files

# Install Jupyter
pip install jupyter

# Launch notebooks
jupyter notebook
```

## Usage Tips

1. **Sequential Learning**: Follow notebooks in numerical order
2. **Practice**: Complete tasks after each topic
3. **Reference**: Use Notes directory for detailed explanations
4. **Experiment**: Modify code cells to understand behavior
5. **Build Projects**: Apply concepts to personal projects

## Python Best Practices

- Follow PEP 8 style guidelines
- Write docstrings for functions
- Use meaningful variable names
- Keep functions focused and small
- Handle exceptions appropriately
- Use comprehensions when readable

## Contributing

Contributions welcome:
- Additional practice problems
- Topic explanations
- Code examples
- Bug fixes

## License

MIT License

## Resources

- [Official Python Documentation](https://docs.python.org/3/)
- [PEP 8 Style Guide](https://pep8.org/)
- [Python Tutorial](https://docs.python.org/3/tutorial/)
