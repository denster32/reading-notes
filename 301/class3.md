# Class 3 Notes - Passing Functions as Props

## Summary of Topics

### React Docs - lists and keys

1. What does .map() return?

- it takes an array and returns the values of that array plus something like a math operator

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

- you would use a list element <li> plus curly braces around the element

3. Each list item needs a unique ____.

- key

4. What is the purpose of a key?

- its a special string attribute that you include when creating lists of elements, its like an identifier

### The Spread Operator

1. What is the spread operator?

- its a useful and quick syntax for adding items to arrays, combining arrays or objects and spreading an array into a functions arguments

2. List 4 things that the spread operator can do.

- copying an array
- concatenating/combining arrays
- using math functions
- using an array as arguments
- adding an item to a list
- adding to state in React
- combining objects
- converting NodeList to an array

3. Give an example of using the spread operator to combine two arrays.

- const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

4. Give an example of using the spread operator to add a new item to an array.

- const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits)
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits])

5. Give an example of using the spread operator to combine two objects into one.

-

const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh()

### How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?

- the increment function is implemented within the person.js file

2. In your own words, what does the increment function do?

- the increment function passes the constructor elements and loops through to identify if the count has changed, if so the count is incremented

3. How can you pass a method from a parent component into a child component?

- this.props.increment is used

4. How does the child component invoke a method that was passed to it from a parent component?

- this .prop.increment is used

## Things I want to know more about
