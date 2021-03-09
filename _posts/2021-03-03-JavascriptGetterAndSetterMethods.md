---
Layout:
Title: "Farisani first blog post on visual studio code"
Date: "2021-02-24"
---

# Introduction
Today I learnt about how to create the getter and setter methods in a javascript code to protect the accessibility of a code 

## Use getters and setters to Control Access to an Object
The getter and setter methods can be set as follows:

class Book {
  constructor(author) {
    this._author = author;
  }
  // getter
  get writer() {
    return this._author;
  }
  // setter
  set writer(updatedAuthor) {
    this._author = updatedAuthor;
  }
} 

In this case the class Book has a constructor together with setter and getter methods to access the the code that will normally not be visible to the user
