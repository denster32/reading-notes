# Class 6 Notes - Problem Domain, Objects, and the DOM

## JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?

- a collection of related data and/or functionality.  usually consists of several variables and functions.

2. What are some advantages to creating object literals?

- sending a single object is much more efficient than sending several items individually.  

3. How do objects differ from arrays?

- both are mutable and can be used to store a list of values.  objects are used to represent a thiing in your code, characteristics are called properties that consist of a key and a value.  they can be accessed, added, changed or removed w dot or bracket notation.  

- arrays are used to create and store a list of multiple itenms in a single variable, useful for ordered collections.  Items can be added and removed from the beginning or end of an array using the push(), pop(), unshift(), and shift() methods.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

- if an object property is held in a variable then you cant use dot notation and must use brackets

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?

- this keyword refers to the current object the code is being written inside. this name refers to spot, this age refers to 2

## Intro to the DOM

1. What is the DOM?

- document objest model -> data representation of objects that comprise structure and content of a document on the web.  programming interface for web documents

2. Briefly describe the relationship between the DOM and JavaScript.

- DOM can be modified w scripting language like JavaScript.  DOM is a Wev API, NOT part of JS.  DOM not part of Node.js.  DOM is independent of any particular programming language.
