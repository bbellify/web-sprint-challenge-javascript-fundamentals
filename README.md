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

- `.map` - an array method that iterates over an array performing a given callback function to each item in the array, returning a new array. This is useful for when you want to do something to each item in a given array. For example, taking a list of users in a database that contains a lot of additional information for each user and returning an array of objects containing just the username and ID#.

- `.reduce` - an array method that reduces an array to a single value based on logic given in the callback function, returning the single value. This is useful for when you want to create a single data point out of a list of properties. For example, you could take an array of house objects that included a square footage property and return the average square footage of the houses in the list.

-`.filter` - an array method that iterates over an array performing a given callback function to find instances in an array that match desired logic, returning a new array. This is useful when you want to find only objects in an array that meet desired specification. For example, you could take an array of users in a database and return a new array of the users who had been members for x number of years. 

2. Explain the difference between a callback and a higher order function.

A higher order function is a function that takes another function as one of its arguments. Some examples of this include the array methods discussed above. A callback function is a function fed into another function as an argument. For example, all of the array methods described above take a callback function.

3. Explain what a closure is.

A closure is when an inner or nested function reaches into an outer function to access values defined outside the inner function. 

4. Describe the four principles of the 'this' keyword.

    1. Global binding - when in the global scope, `this` is bound to the window/console object.
    2. Implicit binding - when invoking a function with a preceding dot, the object left of the dot is the `this`.
    3. New binding - whenever a constructor function is used, `this` refers to the specific new instance of the object created by the constructor function.
    4. Explicit binding - whenever a `.call`, `.apply`, or `.bind` method is invoked, `this` is explicitly defined

5. Why do we need super() in an extended class?

When using a class constructor to make an extended class, `super()` effectively replaces having to explicitly bind `this` with a `.call` on a parent class. Nothing different is happening under the hood, but it reduces necessary lines of code and is a cleaner syntax.


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

