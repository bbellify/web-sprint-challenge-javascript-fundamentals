# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

- `.map` - an array method that takes a callback function as an argument and iterates over all elements of the calling array, executing code defined in the callback. This is useful for all sorts of things, including transforming the data in the calling array or returning only desired data from each element of the calling array. For example, taking a list of objects with a website's users' names, passwords, birthdays, addresses, etc. and returning an array of objects containing only, for example, names and birthdays.

- `.reduce` - an array method that takes a callback function as an argument that reduces an array to a single value based on logic given in the callback function. This is useful for when you want to create a single data point out of a list of properties. For example, a landlord could have a list of objects where each object is a building they own and includes a property for number of current occupants. They could invoke `.reduce` on this array and return the total number of all occupants across all buildings.

-`.filter` - an array method that takes a callback function as an argument that returns a new array consisting of the elements from the original array that produce a `true` output when passed through logic defined in the callback function. This is useful when you want to find only objects in an array that meet desired specification. For example, you could take an array of users in a database and return a new array of the users who had been members for x number of years. 

Similarities include them all being array methods and they all take callback functions as an argument. `.map` and `.filter` both produce new arrays, but `.filter` produces a single value. They all have different use cases, as described above.

2. Explain the difference between a callback and a higher order function.

A higher order function is a function that takes another function as one of its arguments. Some examples of this include the array methods discussed above. A callback function is a function fed into another function as an argument. For example, all of the array methods described above take a callback function.

3. Explain what a closure is.

A closure is when an inner or nested function reaches into an outer function to access values defined outside the inner function. 

4. Describe the four principles of the 'this' keyword.

    1. Global binding - when in the global scope, `this` is bound to the window/console object.
    2. Implicit binding - when invoking a function with a preceding dot, the object to the left of the dot is the `this`.
    3. New binding - whenever a constructor function is used, `this` refers to the specific new instance of the object created by the constructor function.
    4. Explicit binding - when a `.call`, `.apply`, or `.bind` method is invoked, `this` is explicitly defined

5. Why do we need super() in an extended class?

When using the class keyword to make a child class extended from a parent class, calling `super()` in the child's constructor function allows us to pass attributes through the parent class, effectively replacing needing to explicitly bind `this` with a `.call` on the parent class. Nothing different is happening under the hood, but is a friendlier syntax, or syntactic sugar :) 


You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

