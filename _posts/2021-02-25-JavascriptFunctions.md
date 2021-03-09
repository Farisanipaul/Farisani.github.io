---
Layout:
Title: "Farisani first blog post on visual studio code"
Date: "2021-02-24"
---

# Introduction
Welcome to another edisode of learning with Farisani. So today we will be doing a lot of Javascript which include how to use for loops, while loops and if statements.

## Generating a Random Whole Numbers within a specified Range
Here we learnt about generating a whole number which is between two numbers stated as myMin and myMax. We used a function and created a while loop which generates random numbers until a number between the myMin and myMax is generated. The function will not stop running until all the random numbers generated meet the requirements needed. 

'''function randomRange(myMin, myMax) {
  // Only change code below this line
  var testCondition = "false";
  var generateRandom = 0;
  while(testCondition == "false"){
    generateRandom = Math.floor(Math.random() * (myMax - myMin + 1)) + myMin;
    if(generateRandom >= myMin && generateRandom <= myMax){
      return generateRandom;
      testCondition = "true";
    }
  }
  // Only change code above this line
}
'''

## Using the parseInt Function
In this section I learnt about a function that we can parse strings to it and it returns integer values. If the first character in the string can't be converted into a number, then it returns NaN. The function call is parseInt(string) with a value of string inside it.

## Using the parseInt Function with a Radix
In this section the parseInt() function accepts another value which is the radix, which specifies the base of the number in the string. The radix can be an integer between 2 and 36.

## Using the Conditional (Ternary) Operator
The ternary conditional operator is the same as the if,else statement but it is a more simplified way of doing it. So instead of using: 
'''
function findGreater(a, b) {
  if(a > b) {
    return "a is greater";
  }
  else {
    return "b is greater";
  }
}
'''js

the function becomes: 
'''
function findGreater(a, b) {
  return a > b ? "a is greater" : "b is greater";
}
'''js
Which is rather a more simplified way


## Using Multiple Conditional (Ternary) Operators
The terenary statement can be adjusted further to include an else statement condition. Instead of writing the a condition on the second ternary statement we just write a colon and the else return statement.
For example we can represent this as: 
'''
function findGreaterOrEqual(a, b) {
  return (a === b) ? "a and b are equal" 
    : (a > b) ? "a is greater" 
    : "b is greater";
}
'''js
## Using Recursion to Create a Countdown
As we did earlier we stated that a recursion is when a function is called within itself 

## Exploring the Differences Between the var and let Keywords
