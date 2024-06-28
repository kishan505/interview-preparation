# Python Interview Questions

## Beginner

### what is python ?
- Python is a widely-used general-purpose, high-level programming language.
- It was created by Guido van Rossum in 1991 and further developed by the Python Software Foundation.
- It was designed with an emphasis on code readability, and its syntax allows programmers to express their concepts in fewer lines of code.


### what is PEP 8 ?

### What are Python data types?
Python has several built-in data types, including:

- Numeric: int, float, complex
- Sequence: list, tuple, range
- Text: str
- Mapping: dict
- Set: set, frozenset
- Boolean: bool
- Binary: bytes, bytearray, memoryview

### What is the difference between `==` and `is` in Python?

- `==` is an equality operator that compares the values of two objects, 
- while `is` is an identity operator that checks if two objects are the same in memory.  
For example:

```python
a = [1, 2, 3]
b = [1, 2, 3]
c = a

print(a == b)  # True, because the values are the same
print(a is b)  # False, because a and b are different objects in memory
print(a is c)  # True, because a and c are the same object in memory

```

### Is Python a compiled language or an interpreted language?

- Python is both compiled as well as an interpreted language.
- This means when we run a python code, it is first compiled and then interpreted line by line.
- The compilation part is mostly hidden from the user. While running the code, Python generates a byte code internally, this byte code is then converted using a python virtual machine (p.v.m) to generate the output

### What is python interpreter

- Interpreters are the computer program that will convert the source code or an high level language into Machine code (machine level language).

### Difference between Compilers and Interpreters

### Why python is called dynamically typed ?
