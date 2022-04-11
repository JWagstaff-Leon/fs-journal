# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation
Inheritance
Polymorphism
Abstraction
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
The grouping of like concerns to allow for easier debugging and very basic data access protection
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility: a function or class should only do the bare minimum of what it is intended to do
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is a prototype of data and methods; an instance of a class is a realization of that collection of data and methods
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A Proxy object is a wrapper around another object, that intercepts specified operations, and thereby acts as a go-between
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
To promote encapsulation on larger projects, and remove ambiguity as to what role a particular class might serve
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
To interface with the user's controls, and pass data on to services
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
To recieve data from the controller, and format, check, and send data to modify the app state
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
To serve as a blueprint on which the rest of the MVC components are built around
```
