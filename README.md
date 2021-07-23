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

1.  Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each.

    The .map method returns a new array by passing each element to its function and returning the result to the new array-- it does not change the original array. For example, if you want to double the values of an array, but still need the original.

    The .filter method returns specified elements of the original array to a new array. These new elements are included on the basis of the function-- if the function returns true, then that element is included. This can be used to narrow a list of objects etc. to include only those with values that meet a certain criteria.

    The .reduce method combines elements of an array into a single value, using an accumulator value and each index (one at a time with the new accumulator) calculating or returning a new accumulator based on those two values. Can be used to find the sum or product of all the values of the array together, find an extreme value, etc.

2.  Explain the difference between a callback and a higher order function.

    A higher order function receives other functions as arguments. Those functions that are passed are the callback functions.

3.  Explain what a closure is.

    If a function is within the scope of another function, and reaches out of itself for a variable that's defined in the outer function, this creates a closure.

4.  Describe the four principles of the 'this' keyword.

    The 'this' keyword can be bound in four different ways:  
     If it's not given any context, then it binds by default to the window-- this is 'window binding' and is not good.

        If an object has a method using the 'this' keyword, then whenever a variable calls this method, the this is bound to that variable. (The item left of the dot)  This is called implicit binding.

        When we use the .call, .apply, or .bind methods, we can specifically tell what the 'this' keyword is referring to.  This is known as explicit binding.

        The last type of use is called new binding.  When creating a new instance of a class or function, the this keyword inside the function is bound to the new object or function that's being created.

5.  Why do we need super() in an extended class?

    A typical constructor function uses 'parent'.call, and Object.create for inheritance to work with child functions. super() is used together with extends to do the same thing-- only for a class instead.

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
