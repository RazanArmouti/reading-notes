# Readings: In memory storage
## ***Understanding the JavaScript Call Stack***
**1. What is a ‘call’?**  
 The call is the invocation of a function.
**2. How many ‘calls’ can happen at once?** 
 only one call can happen at once.
**3. What does LIFO mean?** 
 LIFO stands for Last In First Out which means the when we call a function that depends on other functions we stack them by the order they were invoked and then execute them in the call stack from top to bottom and free the memory allocated for them after they have been poped out from the call stack.
**4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**
 ![Call stack](https://camo.githubusercontent.com/70bf6b6f60682120033d4e598e23aa9197c2a0e3156c839c7c40db3a04eb4006/68747470733a2f2f692e7974696d672e636f6d2f76692f325a485f316438545956672f6d617872657364656661756c742e6a7067)
**5. What causes a Stack Overflow?** 
 The stack overflow happens when the size of stacked functions exceeds the size of the call stack. One of the primary reasons for that is using recursion (calling the function inside itself ) without exit point.



## ***JavaScript error messages***
**1. What is a ‘refrence error’?**  
 The stack overflow happens when the size of stacked functions exceeds the size of the call stack. One of the primary reasons for that is using recursion (calling the function inside itself ) without exit point.

**2. What is a ‘syntax error’?** 
 syntax error occures when you break the rules of the programming languages. for example if you pass invalid json object to JSON.parse you will end up with syntax error.
**3. What is a ‘range error’?** 
 Range error occures when you try to mutate the lenght of an array for example. you try to put its length to 0 but by mistake you putted it -1 then the range error message will show.
**4. What is a ‘tyep error’?**
 var foo = {}
 foo.bar // undefined
 foo.bar.baz // Uncaught TypeError: Cannot read property 'baz' of undefined
**5. What is a breakpoint?** 
 The breakpoint is a point you choose it to referes to a specific line in your code . By doing this you can debug your code and see the results until this point .
**6. What does the word ‘debugger’ do in your code?** 
 if we write debugger in a specific line in the code then it will create a breakpoint for this line.
 

## ***JavaScript errors reference on MDN***

## Things I want to know more about