# Readings: Game of Greed 3
## ***List Comprehensions***
 In order to keep your code elegant and readable, it’s recommended that you use Python’s comprehension features.
 Writing compact code is essential for maintaining programs and working with teams. 
 Learning to make use of advanced features like list comprehension will save time and improve productivity. 
 1. Create a List with range()
 2. Create a List Using Loops and List Comprehension in Python
 3. Multiplying Parts of a List
 4. Show the first letter of each word using Python
 5. Lower/Upper case converter using Python
 6. Print numbers only from a given string
 7. Parsing a file using list comprehension
 8. Using functions in list comprehensions

## ***Primer on Decorators***
 a decorator is a function that takes another function and extends the behavior of the latter function without explicitly modifying it.
 functions are first-class objects. This means that functions can be passed around and used as arguments, just like any other object (string, int, float, list, and so on).
 It’s possible to define functions inside other functions. Such functions are called inner functions.Python also allows you to use functions as return values. 
 1. They can be reused.
 2. They can decorate functions with arguments and return values.
 3. They can use @functools.wraps to look more like the decorated function.

 to define a decorator, you typically define a function returning a wrapper function. The wrapper function uses *args and **kwargs to pass on arguments to the decorated function. If you want your decorator to also take arguments, you need to nest the wrapper function inside another function. In this case, you usually end up with three return statements.

## ***Debugging with PySnooper*** 