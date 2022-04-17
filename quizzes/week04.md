# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
In asynchonrous code, there can be return values of functions that are promises — meaning the desired return value isn't immediately resolved when the function returns.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is an object that calls a specified callback function whenever the event it's listening for is emitted.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open/Closed - encapsulated code should be open for functionality to be built on top of it, but closed for the base functionality to be changed.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A callback is a function pointer passed as an argument with the assumption that it will be called back later. A higher order function is a function wich takes in or returns a callback function.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is an object that will return the desired value asynchronously when that value is available. By calling the .catch function of a promise, if the promise resolution fails, anything in the .catch function will be run.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
GET
POST
DELETE
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The services
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
To provide an easier route to debugging, better code modularity, and very basic data security.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
Internal Server Error
```