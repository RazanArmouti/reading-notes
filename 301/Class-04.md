# Readings: React and Forms
## ***React Docs - Forms***
**1. What is a ‘Controlled Component’?** 
 A JavaScript function that handles the submission of the form and has access to the data that the user entered into the form.

**2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**
 Typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.

**3. How do we target what the user is entering if we have an event handler on an input field?**
 When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.
 

## ***The Conditional (Ternary) Operator Explained***
**1. Why would we use a ternary operator?**
 Using a conditional, like an if statement, allows us to specify that a certain block of code should be executed if a certain condition is met.
 
**2. Rewrite the following statement using a ternary statement:**
 (x===y)?console.log(true);: console.log(false);

## ***React Bootstrap - Forms***
## ***React Docs - conditional rendering***


## Things I want to know more about