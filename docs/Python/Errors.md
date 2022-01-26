# Errors
---

There are two types of errors in python: compile-time errors and run-time errors.

## Compile-Time Errors (Syntax Errors)
Compile-time errors are errors detected when a program is being compiled. In python, this happens when the interpreter attempts to compile your program into byte code. These errors are usually caused when something is wrong according to the rules of the language.

Before an executable can be created, all compile-time errors must be fixed. Typically, Python will help us identify the error in some way.

For example, take the following code:

```python
print("Hello, World!)
```

This will result in the following error report:

```
File "/Users/abbas/Downloads/tmp.py", line 1
    print("Hello, World!)
                         ^
SyntaxError: EOL while scanning string literal
```