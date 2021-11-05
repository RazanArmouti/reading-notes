# Readings: Game of Greed 1
## ***How to use Random Module***
 The random module provides access to functions that support many operations. Perhaps the most important thing is that it allows you to generate random numbers.
 1. Randint
  If we wanted a random integer, we can use the randint function Randint accepts two parameters: a lowest and a highest number. Generate integers between 1,5. The first value should be less than the second.
 2. Random
  If you want a larger number, you can multiply it.
 3. Choice
  Generate a random value from the sequence sequence.
 4. Shuffle
  The shuffle function, shuffles the elements in list in place, so they are in a random order.
 5. Randrange
  Generate a randomly selected element from range(start, stop, step)

## ***What is Risk Analysis***
 The probability of any unwanted incident is defined as Risk. In Software Testing, risk analysis is the process of identifying the risks in applications or software that you built and prioritizing them to test. After that, the process of assigning the level of risk is done. The categorization of the risks takes place, hence, the impact of the risk is calculated.
 Risk Identification:
  1. Business Risks:
  2. Testing Risks
  3. Premature Release Risk
  4. Software Risks
![Risk Assisment](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2019/08/Picture1-768x422.png)
There are three perspectives of Risk Assessment:
* Effect
* Cause
* Likelihood

## ***Test Coverage*** 
 Test coverage is a useful tool for finding untested parts of a codebase. Test coverage is of little use as a numeric statement of how good your tests are.
 ![Test coverage](https://martinfowler.com/bliki/images/testCoverage/sketch.png)

## ***Big O Notation***

## ***Python Random***
 For integers, there is uniform selection from a range. For sequences, there is uniform selection of a random element, a function to generate a random permutation of a list in-place, and a function for random sampling without replacement.

## ***What is Dependency Injection***
 dependency injection is a technique whereby one object (or static method) supplies the dependencies of another object. A dependency is an object that can be used (a service).
 transferring the task of creating the object to someone else and directly using the dependency is called dependency injection.
 There are basically three types of dependency injection:
 1. constructor injection: the dependencies are provided through a class constructor.
 2. setter injection: the client exposes a setter method that the injector uses to inject the dependency.
 3. interface injection: the dependency provides an injector method that will inject the dependency into any client passed to it. Clients must implement an interface that exposes a setter method that accepts the dependency