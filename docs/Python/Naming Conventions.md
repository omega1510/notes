# Naming Conventions
---

## Variables
The python style guidelines prefer variables to be named with underscores:

```python
my_var = True
```

Personally, I like to use camelCase:

```python
myVar = True
```


## Symbolic Constants
Variables that act as symbolic constants are named in all caps with underscores:

```python
ATOMS_IN_A_MOLE = 6.022E23 # atoms in a mole
```

## Strings
All strings should be used with `""` double quotes, unless a double quote is needed in the string.

## Line Length
There should be no line longer that 80 characters in your code.

## Docstrings
Docstrings can be formatted one of two ways:

```python
"""
Docstring"""
```

or 

```python
##
# Docstring
#
```

I prefer to use the latter.

## Operators
All operators should be 
surrounded by spaces, unless they aren't being used as an operator.

```python
total = x + y
```


## Pep8
Review the [Python Style Guide](https://www.python.org/dev/peps/pep-0008/)

## Black
Format your code with `black --line-length 80 [FILE]` to automagically format it.