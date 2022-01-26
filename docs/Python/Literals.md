# Literals
---

Literals are the raw data that are assigned to variables or constants while programming.
To format these into strings, use [[String Formatting]] or [[f-strings]].

## String Literals
A string literal can be created by writing a text(a group of Characters ) surrounded by the single(”), double(“”), or triple quotes.
See [[Naming Conventions#Strings]] or [Style Guide for Python](https://www.python.org/dev/peps/pep-0008/) for guidelines.

```python
myString = "Hello, World"
```

## Integer Literals
Both positive and negative numbers including 0. There should not be any fractional part.

| Prefix | Result              |
| ------ | ------------------- |
| None   | Decimal Literal     |
| `0b`   | Binary Literal      |
| `0o`   | Octal Literal       |
| `0x`   | Hexadecimal Literal |

```python
myInt = 25
myBinaryInt = 0b0110001 # letter a
```

## Float Literals
These are real numbers having both integer and fractional parts.

```python
myFloat = 2.25
```

## Boolean Literals
These can have a value of `True` or `False`.

```python
myBool = True
```
