## Week Four - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's your favorite project management tool?

I like waffle. It is free and it is customizable for using on an individual project or a group project so you don't have columns that you are not using. It also works well with github.

2. Why do we create staging environments?

Staging environments let us see how are app will work in a production environment without actually putting it in production. It is a layer of protection between development and production.

3. What are the characteristics of a good README (in your opinion)?

Easy to follow setup instructions with examples and screenshots if necessary. It also clearly defines what the code does and what dependencies you need.

4. What's one main improvement you're going to make to your code regarding accessibility issues?

Tab indexes are fairly easy to put in and can provide a lot of help to people that need them. I am also paying more attention the the colors I am using.

5. What are some basic security concerns to be aware of when building applications?

Making sure users can only access information they are supposed to be able to access..ie they can't view admin pages or pages of another user. Also making sure that a user can't put a malicious script into your program.

6. Why is continuous integration helpful/important?

CI has team members integrate thier work at regular intervals, at least once a day, which runs through an automatic build which can help to identify errors early. Won't let you submit code to production that will break another part of the code. Ensures certain percent of test coverage if set up that way.

7. What are some pros/cons of using ReactJS as a frontend tool?

Pros-It is a library so it is lightweight and can be used for only parts of your app instead of having to use it for the whole app. You can create a component and reuse it. It is fairly simple to learn.

Cons-Have to use redux or another library to manage state. Uses JSX which takes some getting used to. A lot is going on in the background so it can be hard to debug some errors because you don't really understand what is going on.

#### Review  

8. What are some characteristics of "good" git workflow?

Commiting frequently and making sure to merge master and run tests before making a pr. Also it is important to use descriptive commit messages. You should make a new branch when working on a new feature, and not commit directly to master.

9. Describe each of the four fundamental concepts of object oriented programming.

Abstraction- reduces complexity, shows only the necessary parts to the user
Encapsulation-putting data and methods that go together(have been abstracted) in a container together called a class. You also protect that data by not allowing outside classes to know the inner workings of the class. Outside classes should only know what is necessary for them to perform their actions. Hiding data this way also makes it so that your code is not so interconnected. If you change something in one class, you don’t want to get a bunch of errors in other classes because they are so connected together. User can not directly access all information from class. Set data to proveate and update them through public methods.
Inheritance-Creating a new class from an existing class.
Polymorphism-Means it can behave multiple different ways. A sub class can have their own behavior and share some of the behaviors of their parent class but not the other way around. You can override behaviors of the parent class to make the child class behave in the right way at the right time. A plus sign might add two numbers or concatenate two strings. It depends on the context it is used in and the program knows which one to use.

10. What's a module in Ruby? What's the difference between a class and a module? What are some good use cases for modules?

Modules do not have state but classes do. Modules can not be instantiated. They are more like libraries of code that can be used across multiple apps. Classes can inherit from another class but modules can not. Classes only inherit from one other class but can include multiple modules. You can use modules whenever you have a chunk of code that you are going to reuse across multiple classes or apps and whenever you don't need state.
