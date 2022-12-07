# Class 7 Notes - OOP and HTML Tables

## Domain Modelling

1. Explain why we need domain modelling

- domain modelling -> process of creating a conceptual model in code for a specific purpose
- describes various entities and constraints that govern the problem domain
- defines vocabulary that can be used within and between technical and business teams

## HTML Table Basics

1. Why should tables not be used for page layouts?

- they reduce accessibility for visually impaired users
- they produce tag soup -> harder to writem debug and maintain
- not automatically responsive

List and describe 3 different semantic HTML elements used in an HTML table.

- table, tr, td

## Introducing Constructors

1. What is a constructor and what are some advantages to using it?

- constructor is a function thats called using new keyword
- when you call it it will : create a new object, bind this to the new object
- run the code in the constructor
- return new object
- its better than creating a new onject, initialzing it and returning it

2. How does the term this differ when used in an object literal versus when used in a constructor?

- in an object literal this enables you to use the dame method def for every object you create, not that useful when when writing out OL by hand

- when you call a new constructor with the new keyword this binds to the new object

## Object Prototypes Using a Constructor

1. Explain prototypes and inheritance via an analogy from your previous work experience.

- inheritance only has one construct, objects -> each object has a private property which holds a link to another object called its prototype -> that prototype has its own prototype and so on and so forth
