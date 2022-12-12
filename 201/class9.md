# Class 9 Notes - Forms and JS Events

## HTML Forms

1. Why are forms so important in web development?

- forms are a means of gathering input data from a user in a structured fashion

2. When designing a form, what are some key things to keep in mind when it comes to user experience?

- the user needs to have clear and concise guidance when inputting data so that the most accurate data is collected

3. List 5 form elements and explain their importance.

- form -> defines the form
- label -> takes the input field
- input -> concerns itself w the type attribute so that the inputted data is in the correct format
- textarea -> represents a multi-line plain text editing control
- button -> accepts a type attribute like submit, reset or button

## Introduction to JS Events

1. How would you describe events to a non-technical friend?

- events are actions or occurences that happen in a system you are programming which the system tells you about so your code can react

2. When using the addEventListener() method, what 2 arguments will you need to provide?

- type and listener -> and optionally options and useCapture

3. Describe the event object. Why is the target within the event object useful?

- event object is a parameter inside and event handler function
- the target property of the event object is always a ref to the element the event occured upon
- the target can be useful to use in other functions or to end loops

4. What is the difference between event bubbling and event capturing?

- event bubbling describes how the browser handles events targeted at nested elements
- event capturing is like event bubbling but the order is reversed, the event fires first on the least nested element and then on successively more nested elements
- today browsers can implement both, but bubbling is the default
