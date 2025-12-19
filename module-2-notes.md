# Module #2: Python

## #2.1: Project 1 - Hospitality Domain Data Analysis

Various aspects of Data Analyst projects such as:

1. Understanding Business Problem
2. Data Understanding
3. Data Collection
4. Data Cleaning
5. Data Transformation
6. Insight Generation

## #2.2: Expense Tracking System

What you will learn:

- Streamlit UI Framework
- FastAPI Backend Framework
- Database Interactions in Python
- Pydantic
- Context Manager
- API Calls Using Requests Package

## #3: Python Setup

Install Python.

Install the classic Jupyter Notebook with:
`pip install notebook`

To run the notebook:
`jupyter notebook`

References:  
[Python Official Website](https://www.python.org/)
[Jupyter Notebook](https://jupyter.org/)
[Install Jupyter Notebook](https://jupyter.org/install#jupyter-notebook)

## #4.1: Variables

- Variables are containers that store data.
- Variables can store different types of data like integer, float, string, boolean etc.
- Rules of naming variables in Python:
    - You cannot use reserve words (or Python keywords)
    - must start with a letter or an underscore _
    - spaces and special character other than underscore _ (like @, #, $, % etc.) are not allowed
    - underscore _ is valid character and can be placed anywhere in a variable name

## #4.2: Numbers

- Integer numbers store whole numbers (without decimal part), e.g., 25, 500, 10000 etc.
- Float numbers store numbers along with their decimal part, e.g., 3.14, 50.5, 1011.33 etc.
- `type(variable_name)` can be used to detect the data type of a variable.
- `/` operator is used for division, `//` is used to retrieve integer part of the division.
- `%` is a modulo operator, it returns the remainder of the division operation.
- `x ** y` = x raised to the power of y
- we can do type casting using functions like `float()`, `int()`, `str()` etc.
- `math` is a handy module in Python that gives access to functions like - `sqrt()`, `floor()`, `ceil()` etc.

### #1.6: Strings

- Strings are immutable, meaning they can't be changed once created.
- We can access specific characters using indexing, like `fullName[5]`.
- We can access substring using slicing, like `fullName[6:12]`, `fullName[6:]`.
- We can use string formatting techniques like f-strings - `f{}` for easier and more readable string composition in Python.
- Python provides many built-in string methods like - `strip()`, `upper()`, `lower()`, `find()`, `index()` etc.

### #1.7: Lists

- Lists allow you to store sequential data.
- Lists are ordered, meaning each item has a fixed position unless explicitly changed.
- Python lists can hold different data types in a single list, including numbers, strings and other lists. This means they are heterogeneous. For example `randomList = [3.14, 'Blue', True]`.
- Lists are mutable, allowing for elements to be added, removed or changed within the same list.
- List slicing lets you access a specific range of elements quickly, using the syntax `someList[start:end:step]`.

### #1.8: If Condition

- If statements execute a block of code only if the condition is true,
enabling conditional logic in programs.
- Use elif to specify additional conditions if the initial if condition fails,
allowing for multiple sequential checks.
- else provides a fallback block of code when all preceding if and elif conditions are false.
- Combine logical operators like and, or, and not within if statements to handle complex
conditional expressions.
- Nested if statements allow for checking multiple layers of conditions,
enabling detailed decision-making processes in code.

### #1.9: For Loop

- For loops iterate over a sequence, such as a list, tuple, or string,
executing a block of code for each item.
- The range() function is often used with for loops to generate a sequence of numbers,
facilitating iteration over a set number of steps.
- Loop control statements like `break` and `continue` can alter the flow of a loop,
break allows to exit the loop and continue allows to skip rest of the statements and jump to the next iteration.
- enumerate() will allow you to access both the index and the element from a list inside the for
loop.

### #1.10: Functions

docstrings
Function documentation in Python is primarily achieved through docstrings. Docstrings are special string
literals that are used to document modules, classes, functions, and methods. They provide a concise and
descriptive explanation of what the code does, its purpose, parameters, and return values.

Positional Arguments Vs Keyword Arguments

Default Arguments

*args Vs **kwargs

lambda
Use this to define quick one liner function.

Built-in functions
User defined functions

---

### #1.11: Dictionaries & Tuples

Tuples are immutable.

Tuple has a fixed size.

Whenever you have a fixed number of items, you don't want to change them,
then you should use tuples.

Big O Notation
O(n)
Hash Maps = One of the data structures

The way Hash Maps are implemented in Python is using Dictionary.

Look up by key is O(1) on average.
Insertion/Deletion is O(1) on average.

Reference  
[Data Structures & Algorithms in Python](https://www.youtube.com/watch?v=_t2GVaQasRY&list=PLeo1K3hjS3uu_n_a__MI_KktGTLYopZ12)

### #1.12: Modules and Pip

Built-in Modules
External Modules
User Defined Modules

NumPy
https://numpy.org/

pandas
https://pypi.org/project/pandas/

scikit-learn
https://scikit-learn.org/stable/


`pip install`

`pip uninstall`

To get version of the package.
`pip freeze | grep numpy`

References  
[The Python Package Index](https://pypi.org/)

### #1.13: File Handling

### #1.14: Classes and Objects

### #1.15: Operator Overloading

### #1.16: Inheritance

### #1.17: Exception Handling

try
except
raise
finally

Python built-in exceptions
[Python > Built-in Exceptions](https://docs.python.org/3/library/exceptions.html)

### #1.18: __main__ function

### #1.19: NumPy

NumPy
Pandas

---

## Reference Links

- [python Official Website](https://www.python.org/)
- [streamlit.io](https://streamlit.io/)
- [Streamlit Crash Course: From Zero to Data App](https://www.youtube.com/watch?v=d7fnzDQ5qM8)
- [IEEE Floating-Point Representation](https://learn.microsoft.com/en-us/cpp/build/ieee-floating-point-representation?view=msvc-170)

---

## Backlog

### #1
Does anyone know the difficulty level of the IBM Data Science HackerRank test that is given before interviewing a candidate? It consists of two coding questions. If anyone has taken this test, please share your feedback, it would be really helpful. Thanks!
