# Script for solving of Quadratic equation
This script allows to solve different quadratic equation. Quadratic equation has view: ax**2 + bx + c = 0. In script there are 2 files: quadratic_equation.py - for solving equation and tests.py - for testing script.

At first, the script calculate Discriminant's value. 
```python
    discriminant = b ** 2 - 4 * a * c
```

Depending on Discriminant's value (D), the script returns 3 options of roots:

In case if D = 0, the script returns 1 root;

```python
    if discriminant == 0:
        return root1, None
```
     
In case if D < 0, the script returns None roots;

```python
    elif discriminant < 0:
        return None, None
```
        
In other case, the script returns 2 roots

```python
    else:
        return root1, root2
```

# How to use
For solving equation, you have to launch file: quadratic_equation.py. Then launch function get_roots(a, b, c), where a, b, c - coefficients of quation. 

For example,

```python
    print(get_roots(-1, 2, 2))
```
For checking, you have to launch file: tests.py.


# How to launch tests

python tests.py


# Project's aim

This code was written for educational aims for project ― [DEVMAN.org](https://devman.org)
