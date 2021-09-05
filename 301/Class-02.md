# Readings: State and Props
## ***React lifecycle***
**1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**
 The ‘render’ happens first.
**2. What is the very first thing to happen in the lifecycle of React?**
 The mounting phase
**3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**
 constructor, render, componentDidMount, React Updates, componentWillUnmount
**4. What does componentDidMount do?**
 This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().setState() can be called here, but it should be used sparingly, because it will cause a rerender, which can lead to perfomance issues.Here we use componentDidMount() to connect to the YouTube API and get videos when the components is rendered.

## ***React Bootstrat Documentation***
 React-Bootstrap replaces the Bootstrap JavaScript. Each component has been built from scratch as a true React component, without unneeded dependencies like jQuery.

## ***Netlify***
 Netlify makes CI/CD, deployment and scaled hosting a commodity and helps enterprises focus on creating great dynamic consumer experiences in a Jamstack world.

## ***React State Vs Props***
**1. What types of things can you pass in the props?**
 Props allows us to pass values from a parent component down to a child component. The values can be any data type, from strings to functions, objects, etc.

**2. What is the big difference between props and state?**
 props passed into componant but state handel inside the componant .

**3. When do we re-render our application?**
 when we want to change something in our application and we will use the state.

**4. What are some examples of things that we could store in state?**
 storing the count in the state but we are not using it in render and also not passing it to other components as a prop. You might be using it just to check how many clicks happened or for some other purpose. But this will make your app re-render for every button click just because you used state.

## ***React Docs - State and Lifecycle***
## ***React Docs - handling events***
## ***React Tutorial through ‘Developer Tools’***


## Things I want to know more about