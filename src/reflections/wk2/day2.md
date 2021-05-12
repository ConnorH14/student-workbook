# Javascript Functions

> What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?

Functions can be written as


function name(parameters){
  //statements
}
Using this function, the definition is hoisted and name() can be used above itself in the code.

let name = function(parameters){
  //statements
}
Setting a function without a name prevents the function from being hoisted, and can be used when the variable name is called.

let name = (parameters) =>{
  //statements
}
The arrow function is a shorter way to write a function.


> What is the difference between Parameters and Arguments?

Arguments are passed into a function, and parameters are used to define what happens to the argument in a function.

> What are higher order functions? Can you provide an example?

Higher order functions are just functions that can accept a function as an argument, or return a function as a result. 

> [Javascript Challenges](https://connorh14.github.io/js-tests-loops-and-arrays/)