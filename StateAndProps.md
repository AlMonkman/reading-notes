# State and Props  
---

The difference between state and props are essential to using React properly. These articles will help us understand and effectively use the two. 

## React Lifecycle  

*1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?*  

Based off the diagaram is appears that the render phase happens before the commit phase. And the 'componentDidMount' Is at the bottom in the commit phase.  

*2. What is the very first thing to happen in the lifecycle of React?*  

The three phases of a components lifecycle are Mounting, Updating and Unmounting. Before any of these can start the constructor for a react component must be called.  

*3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates*  

- constructor
- render
- componentDidMount
- React Updates
- componentWillUnmount

*4. What does componentDidMount do?*  

This method is invoked immediately after a component is mounted. Here you can load anything using a network request or initialize the DOM. 

## React State Vs. Props  

*1. What types of things can you pass in the props?*  

You want to think of props the same way you think of arguments that you pass into a function. 

*2. What is the big difference between props and state?*  

Props are passed into a component and handled outside of the component. Where as state is handled inside of that component. 

*3. When do we re-render our application?*  

When you change the state inside of your application it is going to re render your application. But Props you have to change outside of the component. This is where state is very useful, especially when changing things based on the user's input.

*4. What are some examples of things that we could store in state?*  

One main thing that is very usefull to store in state is the user's input, we can then access this later and use it when needed. If you are handling a piece of information inside one component only then you will use state, if you are handling information outside that component then you need to pass it in using props. You also use props for static things that will not be changing.  

## Things I want to know more about.  

