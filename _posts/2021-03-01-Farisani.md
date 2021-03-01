---
Layout:
Title: "Farisani first blog post on visual studio code"
Date: "2021-02-24"
---

# Introduction 
Todays blog is about Javascript ES6. ES6 introduces some new concepts which were not covered in the basics of javascript course.

## Difference between using the let and var keyword in the javascript environment
So the main diffence between the let and var keyword is visible when for example the keywords are used inside an if statement or a for loop. When both are defined outside of the function, for loop or if statements they operate as global variables.

## Using the const keyword and mutability
The const keyword is used when the variable being defined will remain unchangable throughout the code. The only time when it becomes changable is when working with arrays. The arrays are mutable and allow the code to be changed.

## Intriducing the Object.freeze() operator for const
The Object.freeze() command can be used when we want the const defined keyword to remain const and also to become immutable.

## Using the arrow function to write a Concise Annonnymous Function
If we want to pass a function to another function then the function defined will not be used anywhere else in the code and the ES6 provides a simpler method of doing this. for example the function definition syntax can be changed from: 

const myFunc = function() {
  const myVar = "value";
  return myVar;
}

to:

const myFunc = () => {
  const myVar = "value";
  return myVar;
}

by using the arrow function 

## Passing arguments into arrow function
Just like the normal function, you can also pass arguments to arrow functions.

## Setting up default parameters for your function
The default parameters are returned when a call is made to the funcion but no values are passed to the function.

## Using the rest parameter with function parameters
The rest parameter allows us to call any number of arguments into a function and still do the work on it.

## Using the spread operator 
The spread operator works with arrays and cannot be assigned to a variable if not inside an array.

## Using Destructuring Assignment to Assign Variables from Objects

## 
