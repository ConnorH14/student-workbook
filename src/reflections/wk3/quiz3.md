# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?

Encapsulation, Abstraction, Inheritance, Polymorphism

**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
staff[property]

**3.** What is Encapsulation?

Encapsulation spreads out code and only is accessed when it is needed, and only through the intended method.

**4.** What does the S stand for in the `SOLID` principles?

Single responsibility

**5.** What the difference between a `class` and an instance of a `class`?

A class defines a place for the values of a class instance

**6.** What is a `Proxy` object?

It is an object that can wrap another object

**7.** What is the purpose of the `MVC` pattern?

It is to seperate parts of your code out into what interacts with the page, and how the data is manipulated. 

**8.** What is the job of the `Controller` in the `MVC` Pattern?

The controller passes data to and from a service, and manipulates the DOM.

**9.** What is the job of the `Service` in `MVC`?

The service takes in data from a controller, and returns the new data.

**10.** What is the job of the `Model` in `MVC`?

The model defines classes, which can be given instances in the App state.

