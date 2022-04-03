# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
const
let
var
```

**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a subprogram acting on 0 or more parameters that can be run through its name in the future
```

**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S - Single Responsibility; a class or function should do only the 1 thing it's supposed to do

O - Open/Closed; a class or function should be easy to expand upon without changing the base class or function

L - Liskov Sustitution; a class should be able to be substituted by any class that inherits from it

I - Interface Segregation; a class that is inherited from should not include unnecessary functions for the inheriting class

D - Dependancy Inversion; a class that inherits from other classes should rely on abstract classes' functions instead of functions from the inherited class
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 

What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
the index is 2 because it is 2 positions away from the beginning
```

**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them);
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if(true === true)
```

**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
final-expression

i++
```

**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model

the html file of the webpage
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Undefined
Null
Boolean
NotANumber
BigInt
Number
String
Array
Object
```

**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
a parameter is the variable declaration in the function; an argument is the what is passed to the function when it is called
```

**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
a primitive value is passed by value; a reference is passed by reference, or as an address
```