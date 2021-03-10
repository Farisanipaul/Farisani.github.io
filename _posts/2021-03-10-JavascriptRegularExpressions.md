---
Layout: 
Title: "Regular Expressions"
Date: "2021-02-24"
---

# Introduction
Regular expressions are used in programming languages to match parts of strings. Patterns must be created to help with matching.

## Using the Test Method 
In this type of testing, the // are used to place the word or text to search from a string.
an example from freecodecamp is shown below for more understanding.

''' let testStr = "freeCodeCamp";'''
''' let testRegex = /Code/;'''
'''   testRegex.test(testStr); '''

## Matching a Literal String with Different Possibilities 
The | operator is used to include multiple text to test in one go and if the test is passed the searched items will be recorded.

## Ignoring Case While Matching
We can also ignore the case by icluding an i after the double slash. for example this can be written as follows:
/word_to_test/i   

This option will ignore the case of all the words being tested.

## Extracting Matches
This option can be used to extract matching items or words being searched.

## Finding More Than the First Match
To search or extract a pattern more than once, the g flag can be used which is placed in the same place as the i for ignoring the uppercase.

## Match Letters of the Alphabet
The [a-e] range allows us to test for lettes between a and e. Any range can be made depending on what is required. 

## Match Numbers and Letters of the Alphabet
We can also include letters and numbers at the same time and this is done by /[a-z0-9]/.