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
- .map() is used when you want to convert data. it doesn't change or manipulate the original array that its converting but it will instead return a brand new array and requires a return statement. You would want to use this when you want to make a new array of information without changing the old one.
- .reduce() is usually used for multiplication and addition but can be used for anything. It does't return a new array but instead returns a single value. And example of when you would want to use this would be when you want to find the sum of numbers like, distance traveled or a population of cities in your array.
- .filter() will take data and filter it as a boolean so if something is true it will include it in the new array and if it is false it gets excluded. like .map() this also requires a return statement and creates a new array without manipulating the old one. .filter() is especially useful when you only want a certain object/piece of information to be passeed in to a new array.

2. Explain the difference between a callback and a higher order function.
 - Higher Order Functions receive (they receive other functions as parameters), Callback functions are passed in (they are passed in to other functions as arguments).

3. Explain what a closure is.
 - closure allows us to put functions together. It lets us access functions from a parent level scope in child level scopes even after the parent function is terminated. In closures we can pass variables down but we can never pass them back up.

4. Describe the four principles of the 'this' keyword.
  - Window binding: if 'this' hasn't been given any biased it will be returned the window which is the global object in node or undefined in strict mode. window binding is hardly ever seen in use any more.
  - Implicit binding: this is applied to objects with methods. When the function (method) is invoked, it is saying look to the left of the dot. that is what 'this' refers to.
  - Explicit Binding: we tell a function what the 'this' keyword should be using (.call, .apply, or .bind) 
  .call will invoke the function and you pass it in your argument one by one. 
  .apply invokes the function and you you pass your argument in as an array
  .bind passes in the argument one by one but doesn't immediately invoke the function. What it does instead is return a brand new function that can be invoked later.
5. Why do we need super() in an extended class?
    - super is needed to execute ein the sense that extends tells super what to do. the combination of extends and super do what object.create and parent.call did/does

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

