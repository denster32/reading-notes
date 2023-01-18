# Class 9 Notes - Functional Programming

## Summary of Topics

### Functional Programming Concepts

1. What is functional programming?

- Programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing state and mutable data

2. What is a pure function and how do we know if something is a pure function?

- returns the same result if given the same arguments
- does not cause observable side effects
- not a pure function if it reads external files
- can't rely on a random number generator

3. What are the benefits of a pure function?

- esaier to test, don't nned to mock anything

4. What is immutability?

- unchanging over time, the state of pure functions cannot change after creation

5. What is Referential transparency?

- pure functions + immutable data = referential transparency

### Node JS Tutorial for beginners

1. What is a module?

- allows you to break up your code into separate files, makes it easier to maintain code-base
- import from external files with import statement

2. What does the word ‘require’ do?

- its a function that has a file path as an argument
- it goes through these steps: resolve and load, wrap, execute, return exports, caching

3. How do we bring another module into the file the we are working in?

- import it: named exports are constructed using curly braces, default exports are not

4. What do we have to do to make a module available?

- either import or export depending on need
