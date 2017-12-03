## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. What's the most useful thing you learned from completing the intermission week work?

I think completing sorting suite gave me a lot confidence. I took a udemy course on javascript over the break and then tried to do sorting suite and found that I was able to do it without too much difficulty.

2. What are some tools to help debug JavaScript code?

The one I use the most is console.lot, but I have gotten much more comfortable using debugger and the dev tool panels in chrome to help debug as well.

3. What are some tools you need in order to unit test your JavaScript?

You need mocha and the chai libraries.

4. What is the syntax for invoking a function?

You would write the name of the function (or the variable that holds the function) and then put () with parameters if the function needed them.

5. What is CORS?  

I had to look this one up. All I knew about this without looking it up was that is a problem we will come across when we try to link up our backend and frontend repos. It stands for cross origin resource sharing. It determines whether it is safe to allow restricted resources on a webpage to be requested by another domain.

6. How do we enable CORS?

I think you do it in the request headers with a HTTP Options method?????

7. What's `this` in JavaScript?

This is a keyword that tells you the context that a function was invoked in. Usually...it also does some really weird stuff and it is best to just throw a debugger or console.log in and check what it is.

8. What is Webpack and why is it useful?

Webpack gets all of your CSS, JavaScript, and image files and bundles them together in one file for each type so that the browser can interpret them better and faster. This is useful, not only for speed, but because you as the developer don't have to try and figure out the order that files should be loaded in. Webpack does it for you.

9. When/why do you want to use event delegation?

Event delegation is when you put a listener on a parent node instead of the node you are actually trying to target. Because events will bubble up, if you put the listener on the parent it will get triggered when the child event is put into action. You would want to this because you might want a listener on something that is not currently on the page. By putting the listener on the parent, when the target is actually on the page, the listener will still work.

10. What's `npm` and what do we use it for?

This stands for node package mangager. It is like bundler for rails and allows you to use packages of code(like ruby gems) in your program.



#### Review  
11. What's the MVC design pattern? Describe each part of MVC.

MVC stands for model, view, controller. It is the way Rails handles HTTP requests/responses. When a request comes in, the router decides which controller to send it to. The controller is kind of like a traffic cop that decides what to do with the request and where it needs to go. If the request needs information from the database the model handles getting that information and sending it back to the controller. The controller then sends that information to the view which contains the html to actually render the page that was requested.

12. What are a few ways to optimize a Rails application?

First you need to measure the load times with a program like New Relic so that you know what pages are loading slow and then you should try to clean up that code to make it faster. If it is still slow, you can use background workers or cache data that you will frequently use, although this makes new headaches like knowing when to update and invalidate the cache.

13. What's a background worker? When would we want to use a background worker?  

A  background worker completes a task or tasks while allowing the rest of the application to keep running. You would use a background worker for things like sending emails that don't need to happen to make the rest of your app work and tend to take a lot of time. You can send your response and then complete the task.
