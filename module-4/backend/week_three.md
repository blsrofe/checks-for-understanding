## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?

Node allows you to run javascript outside of the browser. It uses the v8 engine but adds additional functionality that is not available in the browser so that you can use it for a backend.

2. What is Express? What is Express similar to in the Ruby world?

Express is built on top of node and is like Rails in the ruby world. It gives you a framework to use javascript to write server side code. It takes things that node has and makes them easier to work with similar to what jquery does for client side javascript.

3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.

`app.post('/api/v1/foods', FoodsController.postFood)`

The controller will then take in the body of the request and make the database call with that information.

4. What do we use Knex for?

Knex allows you to interact with your database.

5. How **could** you organize your code to follow the MVC design pattern in your Quantified Self project?

You have a server.js file that acts as your routes file and calls functions that you have built in you controller folder which in turn calls functions in your model folder which interact with the database.

6. How do you execute raw SQL in node?

You use knex and set knex equal to the variable database and then you can call database.raw.

7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?

The disadvantages are that it can generate CORS issues when they try to talk to each other. The advantages are that you can change parts of one without affecting the other one. You could also talk to different backends. For example, in QS it was helpful to be able to have some routes going to the rails api and change them over as we built new routes in the node api. We didn't have to switch the whole thing at once.

#### Review  

8. Describe DNS.

DNS is the domain name system. It changes domain names into IP addresses. It is like a phone book for the internet.

9. What does writing clean code mean to you?

Writing clean code in general means writing code that other developers will be able to easily understand or code that you can easily understand when you come back to it. Generally that means following best practices such as not repeating yourself and keeping methods and functions short and giving them good names. It also means following conventions.

10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality? Hint: think about what tables you would need in the database, how those records would relate to each other, and good OOP.  

You would need classes for rooms, customers, staff, meeting_spaces and reservations. Rooms and meeting_spaces would basically just hold state about themselves such as square_footage and types of beds or max occupancy. Reservations would be responsible for taking in reservations for rooms or meeting spaces from customers and knowing which rooms and meeting spaces are booked on which days. Customers would be responsible for making, deleting and updating reservations.
