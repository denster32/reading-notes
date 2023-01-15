# Class 2 Notes - React

## Summary of Topics

### React Lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

- The render phase occurs during the nounting phase, the componentDidMount method is invoked immediatley after the component is mounted

2. What is the very first thing to happen in the lifecycle of React?

- The very first thing to happen is that the constructor component is called

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

- Constructor, render, componentDidMount, componentDidUpdate, componentWillUnmount

4. What does componentDidMount do?

- This method is invoked after the component is mounted.  This is the place to set up subscriptions.  

### React State vs Props

1. What types of things can you pass in the props?

- You can pass the counting component, the intital count, and the title or display components inside of the props

2. What is the big difference between props and state?

- The big difference is that props are passed into a component, like a function, and state is managed within a component

3. When do we re-render our application?

- The application is re-rendered whenever there is a change in their state or props

4. What are some examples of things that we could store in state?

- We can store things that may need to be changed such as count

## Things I want to know more about
