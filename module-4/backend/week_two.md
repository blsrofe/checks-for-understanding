## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. What's one difference between ES5 and ES6?

  ES6 allows you to use arrow syntax and string interpolation and ES5 does not.

2. What's the difference between asynchronous and synchronous JavaScript?

  Synchronous javascript means everything happens in order and whatever is next in line to happen has to wait for the thing before it to finish before it can start. Asynchronous javascript is when you send something to the brower's api to happen when another event is finished through a callback.

3. What are the four pillars of Object Oriented programming?

  inheritance, abstraction, polymorphism, encapsulation

4. What are some tools available in JavaScript to help you write object oriented code?

  You can create classes by using constructor functions and you can use inheritance through prototypes.

5. What are some key concepts to be aware of when refactoring your JavaScript?

  Not leaving commented out code and extra whitespace, making code DRY,  not mixing ES5 and ES6 syntax, having really long methods and blocks of logic that are nested, and breaking SRP.

6. What's a callback function and what are some reasons when we use/need callback functions?

  A callback function is when you pass in a function to another function to be completed at a later time. You might want to use them when you are making ajax calls or for event listeners or enumerables.

7. What are the different scopes of variables in Javascript? When would you want to define global variables?

You have a global scope and the scope within a function. You would want to use a global variable if you wanted to have access to it in all functions throughout your code.

8. What's the difference between `==` and `===` in JavaScript?

  === will not convert datatypes from one type to another but == will attempt to change one data type to another to make them equal so the number 5 and the string "5" will be considered the equal.

9. Why do front end frameworks exist?

  Front end frameworks exist to give you a structure to work off of that has already solved some common problems for you. They allow you to do complex tasks more easily.

#### Review  

10. Why do people say "HTTP is stateless"?

  The server does not remember anything about previous requests that have been made and who made them unless cookies are passed.

11. Describe a RESTful API.

  A restful API uses get, post, put, patch and delete requests. It follows REST protocols of having the frontend and backend separate from each other so either can be replaced independently of the other one. It is stateless and sessions are stored on the front end. Browsers can cache responses from the server to improve performance.

12. What are some main characteristics of a team following an agile workflow?

  Teams using agile are constantly pushing out new features to get feedback instead of waiting until everything is finished. They work in slices, doing a little design, a little testing, and a little coding to get something that works.

13. What are some advantages **and** disadvantages to using OAuth to authenticate a user?

  Advantages-You are using a trusted resource to store and manage passwords so you don't have to mess with it. Their site is probably more secure than yours.
  Disadvantages-The user must have an account with the site you are using oauth with and if that site goes down your oauth won't work.
