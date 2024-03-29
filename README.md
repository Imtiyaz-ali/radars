==============================================================
                    Classes Documentation
==============================================================

1. Class: Mather

    Description:
    A simple class for performing mathematical operations like addition and subtraction.

    Methods:
    - __init__(self): Constructor method to initialize the class with a default value for showProgress.
    - add(self, x, y): Method to add two numbers x and y. Displays a progress message if showProgress is True.
    - sub(self, x, y): Method to subtract y from x. Displays a progress message if showProgress is True.

    Usage:
    ```python
    # Usage example:
    m = Mather()
    result = m.add(5, 3)  # Output: 8
    ```

    Explanation:
    - The add method adds two numbers and returns the result.
    - The sub method subtracts the second number from the first and returns the result.

2. Class: Randomer

    Description:
    A class for generating random integers and floating-point numbers within a specified range.

    Methods:
    - __init__(self): Constructor method to initialize the class with default values for start, end, and showProgress.
    - random_integer(self, start=0, end=100): Method to generate a random integer within the specified range [start, end].
    - random_all(self): Method to generate a random floating-point number between 0 and 1.

    Usage:
    ```python
    # Usage example:
    r = Randomer()
    integer = r.random_integer()  # Output: Random integer between 0 and 100
    random_num = r.random_all()   # Output: Random floating-point number between 0 and 1
    ```

    Explanation:
    - The random_integer method generates a random integer within the specified range.
    - The random_all method generates a random floating-point number between 0 and 1.

Make sure to set showProgress attribute to True if you want to see progress messages while using the classes.
