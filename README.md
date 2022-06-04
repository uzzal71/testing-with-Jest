# testing-with-Jest
Learning End-to-End Testing with Jest

# Contents

## Introduction
1. Create comprehensive end-to-end tests with Jest
2. Prerequisites and learning objectives
3. Exercise files

## 1. End-to-End Test: Basics
4. Introduction to test-driven development (TDD)
5. Fundamentals of unit tests
6. Overview of integration tests
7. Basics of end-to-end tests

## 2. Project Setup: Recipe App
8. Template: Node.js/Express project setup
9. Testing endpoints on Postman
10. Introduction to Jest
11. Jest setup

## 3. End-to-End Test with Jest
12. Test the Login endpoint
13. Finish up on Login endpoint test
14. Test the Create endpoint
15. Finish up on Create endpoint test
16. Test the Read endpoint
17. Test the Update endpoint
18. Finish up on Update endpoint test
19. Test the Delete endpoint

## 4. Test Coverage
20. Test error handling
21. Finish up on test error handling
22. Run test automatically

## Conclusion
23. Next steps

## Introduction

#### 1. Create comprehensive end-to-end tests with Jest
To Verify the functionality of your entire application, to easily revalidate this functionality within seconds, and for continuous integration, you need end-to-end testing. In this course We are going to start with the basics of Test-Driven Development, touching on the different types, and moving on to particially write an end-to-end test for (mumbles) web service application, built with Node.js and MongoDB using Jest, testing the applocation workflow from beginning to end with a high code coverage. I am Uzzal Kumar Roy and experienced Software Engineer in building Scalable Distributed Software Systems that meets business needs in diverse industries. I am excited to welcome you to my course titled "Learning End-to-End Testing with Jest." Let's get started.

#### 2. Prerequisites and learning objectives
- RestfulAPI
- NodeJs
- ExpressJs
- MongoBD
- Mongoose
- ES6

This course makes use of a RESTful Node.js Expres application.
Therefore, to make the most out of this course, you need to have practical experience
writing RESTful applications with Node.js and Express. If you're new to writing RESTful API
With Node.js and Express or need to review them, I recommend searching the library for courses On Building a RESTful API with Node.js and Express.
Experience with ES6 syntax is essential to follow along. I will use the ECMAScript 6 standard,
also know as ES6, throughout this course. If you are not familiar with ES6, we have a course to help.
Search the library for Switching to ES6 in Node.js in the library.
Our project template uses Mongoose ORM to save our retrieve data fro a mongoDB.
So, experience with mongoDB and Mongooses is essential. I am developing on Windows 10 and using Visual Studio Code as my code editor.
Feel fress to follow along on any operating system and code editor of your choice.

#### 3. Exercise files
The source code for this course, is on GitHub. The repository is built in such a way that, 
there are tow branches for each coding video of this course.
You can use the branch button to switch to a specific branch
and see how the code looks at the beginning or end of a specific video.
Foe example, the branch tied to zero, two, zero on B will show you, how the code
looks at the beginning of the video with video number zero, two, zero, one.
If you want to, you can download any of these branches by first switching to the branch
and then hitting the Code button, And clicking on Download ZIP.
You can also, clone this repository into your local machine
by clicking on this button, to copy the URL and then use the Git clone command,
followed by the link you just copied, to save the sourse code to your local machine.
If you need more help on GitHub, please search the library for a course on GitHub.
Otherwise, let's get right into this course.

## 1. End-to-End Test: Basics

#### 4. Introduction to test-driven development (TDD)
What Test Driven Development is, first, you should know that Tests or Test Cases
are simple software requirements adn specifications derived from Use Cases and User Stories.
Test Driven Development, TDD, is a software development process relying on software requirements
beign converted to test cases before software is fully developed and tracking software development by
repeatedly testing the software against all test cases, as opposed to software being developed first
and test cases created later.
Test Driven Development is also called Test First Development because you first writte a test
before you write just enough production code to fulfill that test
and then go on to refactor the production code.
Let's talk about the life cycle of Test Deiven Development. It spins around five steps
Which are repeated continuously all through the agile methodology in software development.
- Write a test
The first step is to write the test. In Test Driven Development, the adding of a new feature begins by writing a test that passes if the feature's specifications are met.
This is in contrast with the usual practice where unit tests are only written after code.
- Test Fails
For the second step, you affirm the test fails. Run all tests. The new test should fail.
This is to validate that the test is working correctly and new code is needed for the desired feature.
- Write code to pass the test
In the third step, you will write code to pass the test. Write the simplest code that passes the new test.
Inelegance code is aceptable as long as it passes the test. The code will be refactored in step five.
You should not write code beyond the tested functionality.
- Test Passes
Four the fourth step, you will affirm the tet passes. Run all tests.
They should all now pass. If any fails, the new code must be revisited until they pass because the new code must meet the test requirements
and not break existing features.
- Refactor
Step five is Refactor. Remove hard-coded test data and refactor as needed for readability and maintainability, running tests after each refactor
to ensure that functionality is preserved.
Finally we will repeat this cycle for each new piece of functionality.
Tests should be small and incremental and commits made often. That way, if new code fails some tests
you can simply undo or revert rather that debug excessively.
Test Driven Development makes you focus on requirements before writing code. And some of its benefits include 

- improved code quality
- detauked product documentation
- Reduced product budget
- Reduced bugs

There are three major types of Test Driven Development.Namely
- Unit Tests
- Integration Tests
- End to End Tests

In the coming videos, we will discuss each of these types of TDD in detail.
