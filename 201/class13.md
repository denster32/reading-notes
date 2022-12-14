# Class 13 Notes - 

## Local Storage and How to Use it on Websites

1. Why would a developer use local storage for a web application?

- HTTP is stateless which means the state will be reset when the application is closed
- local storage allows you to keep a key on the users computer so that the previous state can be reinstated

2. What information should not be stored in local storage?

- You would not want to store objects bc only strings are allowed

3. Local storage can store what type of data? How would you convert it to that type before storing?

- local storage can only store strings in the different keys
- You can work around this by using the native JSON.stringify() and JSON.parse() methods: