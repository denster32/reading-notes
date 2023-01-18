# Class 5 Notes - Putting it all together

## Summary of Topics

### React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?

- that a component should ideally do one thing, if it grows and does more it should be broken down into subcomponents

2. What does it mean to build a ‘static’ version of your application?

- Static apps render in the browser without the need for server side processing.
- All the rendering of HTML, CSS and JavaScript is done on the client side

3. Once you have a static application, what do you need to add?

- The next step is to trigger changes for interactivity through state

4. What are the three questions you can ask to determine if something is state?

- Is it passed in from a parent via props? If so prob not state
- Does it remain unchanged over time? If so prob not state
- Can you compute it based on any other state or props in your component? If so prob not state

5. How can you identify where state needs to live?

- Identify every component that renders something based on state
- find common owner component for all components using the state
- if no component makes sense, create new component to hold state and add it to hiearchy at appropriate level

### Higher order functions

1. What is a “higher-order function”?

- Higher order functions allow us to abstract over actions, not just values
- Can write functions that write functions
- Can write functions that change other functions
- Can write functions that provide new types of flow control

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

- Its comparing m and n and returning true bc m IS greater than n and the value is a boolean

3. Explain how either map or reduce operates, with regards to higher-order functions.

- map method tranforms an array by applying a funciton to all of its elements and builds a new array from the returned values
- reduce method builds a value by repeatedly taking a single element from an array and combining it with the current value

## Things I want to know more about
