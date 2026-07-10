# special_methods# Python Magic Methods (Dunder Methods)

## Overview

This project demonstrates some of Python's most commonly used **magic methods** (also called **dunder methods**). Magic methods let you customize how your objects behave with built-in functions and operators.

## Topics Covered

1. `__init__()` – Constructor used to initialize object attributes.
2. `__str__()` – Returns a human-readable string representation of an object.
3. `__repr__()` – Returns the official string representation of an object.
4. `__len__()` – Defines the behavior of the `len()` function.
5. `__eq__()` – Defines how objects are compared using the `==` operator.
6. `__add__()` – Overloads the `+` operator.
7. `__sub__()` – Overloads the `-` operator.
8. `__mul__()` – Overloads the `*` operator.
9. `__getitem__()` – Enables indexing using square brackets (`[]`).
10. `__setitem__()` – Enables assignment using square brackets.
11. `__contains__()` – Enables membership testing with the `in` keyword.
12. `__call__()` – Makes an object callable like a function.
13. `__iter__()` – Returns an iterator object.
14. `__next__()` – Returns the next item during iteration.
15. `__bool__()` – Defines the truth value of an object.
16. `__del__()` – Destructor called when an object is about to be destroyed.

## Requirements

* Python 3.x

## Running the Examples

Save each example in a Python file or combine them into one script, then run:

```bash
python filename.py
```

## Learning Outcomes

After completing this project, you should be able to:

* Understand Python magic methods.
* Customize object behavior.
* Overload operators.
* Create iterable and callable objects.
* Implement indexing and membership testing.
* Control boolean evaluation.
* Understand when constructors and destructors are executed.

## Conclusion

Magic methods are a key part of Python's object-oriented programming model. They allow custom classes to integrate seamlessly with Python's built-in syntax and functions, making your code more intuitive, reusable, and expressive.

