# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?

var, let, and const.

**2.** What is the definition of a function?

A function is a block of code that can be called to run somewhere else in the code.

**3.** What are the `SOLID` principles?

Single Responsibility, Open closed principle, Liskov substitution principle, Interface segregation principle, Dependency Inversion Principle
SOLID principles refer to object oriented programming and give a structure for design patterns in object oriented software development. 

**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?

The index of the pineapple is fruit[2] it is 3 positions from the start and counting starts at 0.

**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?

you.friends.push(them)

**6.** Give an example of a JavaScript `Conditional`:
A JavaScript conditional would be something like == or >=, its a statement that checks if something is true, like if x is greater than or equal to y.

**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
The last space in the for loop is the update action, and it occurs at the end of every iteration.
I would use i++ to increase i every iteration.

**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?

DOM stands for Document Object Model, and the first file accessed to render the DOM is the html file.

**9.** What are the `9` ECMAScript types as defined by MDN?

undefined, Boolean, number, String, BigInt, Symbol, Object, Function, null

**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?

Arguments are passed into parameters in a function. The paramater allows different arguments to be passed into it, but all are defined as the parameter in the function. 

**11.** What is the difference between a `primitive` value and a `reference` value?

A primitive value can be undefined, null, boolean, number, string or a symbol. A reference type is an object or an array.

>[Checkpoint Two](https://connorh14.github.io/auto-clicker/)