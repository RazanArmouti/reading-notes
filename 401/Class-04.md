# Readings: Topic
## ***Classes and Objects*** 

## ***Thinking Recursively***
 Recursive function is a function defined in terms of itself via self-referential expressions.
 This means that the function will continue to call itself and repeat its behavior until some condition is met to return a result. All recursive functions share a common structure made up of two parts: base case and recursive case.
 When dealing with recursive functions, keep in mind that each recursive call has its own execution context, so to maintain state during recursion you have to either:

Thread the state through each recursive call so that the current state is part of the current call’s execution context
Keep the state in global scope
A data structure is recursive if it can be deﬁned in terms of a smaller version of itself. A list is an example of a recursive data structure.

## ***Pytest Fixtures and Coverage*** 
 pytest, a library for testing Python code.fixtures are used differently from global variables. 
 100% code coverage doesn't mean that your code is perfect or that it lacks bugs. But it does give you a greater degree of confidence in the code and the fact that it has been run at least once.

 how can you include code coverage with pytest? It turns out that there's a package called pytest-cov on PyPI that you can download and install. Once that's done, you can invoke pytest with the --cov option. If you don't say anything more than that, you'll get a coverage report for every part of the Python library that your program used, so I strongly suggest you provide an argument to --cov, specifying which program(s) you want to test. And, you should indicate the directory into which the report should be written.

## ***Pytest Fixtures***
 pytest fixtures are designed to be explicit, modular and scalable.
 In testing, a fixture provides a defined, reliable and consistent context for the tests. This could include environment (for example a database configured with known parameters) or content (such as a dataset).

Fixtures define the steps and data that constitute the arrange phase of a test (see Anatomy of a test). In pytest, they are functions you define that serve this purpose. They can also be used to define a test’s act phase; this is a powerful technique for designing more complex tests.

The services, state, or other operating environments set up by fixtures are accessed by test functions through arguments. For each fixture used by a test function there is typically a parameter (named after the fixture) in the test function’s definition.

We can tell pytest that a particular function is a fixture by decorating it with @pytest.fixture.
pytest does its best to put all the fixtures for a given test in a linear order so that it can see which fixture happens first, second, third, and so on. If an earlier fixture has a problem, though, and raises an exception, pytest will stop executing fixtures for that test and mark the test as having an error.

