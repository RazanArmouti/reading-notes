# Readings: Passing Functions as Props
## ***React Docs - lists and keys***
**1. What does .map() return?**
 It is return an array.
 
**2. If I want to loop through an array and display each value in JSX, how do I do that in React?**
 we loop through the numbers array using the JavaScript map() function. We return a li element for each item. Finally, we assign the resulting array of elements to listItems
 
**3. Each list item needs a unique**
 a Key
 
**4. What is the purpose of a key?**
 Keys should be given to the elements inside the array to give the elements a stable identity:

## ***The Spread Operator***
**1. What is the spread operator?**
 The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
 
**2. List 4 things that the spread operator can do**
 * Copying an array
 * Concatenating or combining arrays
 * Using Math functions
 * Using an array as arguments
 
**3. Give an example of using the spread operator to combine two arrays.**
 const myArray = [`🤪`,`🐻`,`🎌`]
 const yourArray = [`🙂`,`🤗`,`🤩`]
 const ourArray = [...myArray,...yourArray]
 console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
 
**4. Give an example of using the spread operator to add a new item to an array.**
 const fewFruit = ['🍏','🍊','🍌']
 const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
 console.log(fewMoreFruit) 

**5. Give an example of using the spread operator to combine two objects into one.**
 const objectOne = {hello: "🤪"}
 const objectTwo = {world: "🐻"}
 const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
 console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
 const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
 objectFour.laugh() // 😂😂😂😂😂


## ***How to Pass Functions Between Components***
**1. In the video, what is the first step that the developer does to pass functions between components?**
 Create the function

**2. In your own words, what does the increment function do?**
 increased the value of the state in value each time you call it.

**3. How can you pass a method from a parent component into a child component?**
 using props

**4. How does the child component invoke a method that was passed to it from a parent component?**
 via this.props
 

## ***React Tutorial through ‘Declaring a Winner’***
## ***React Docs - Lifting State Up***


## Things I want to know more about