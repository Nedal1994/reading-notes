# Read03 Summary

![middleware](https://networkinterview.com/wp-content/uploads/2021/05/middleware-dp.jpg)

Middleware is based on a software that provides services to applications instead of what its OS is offering such as data management, application services, messaging, authentication & API management. It helps developers build applications more efficiently because it acts like the connective tissue between applications, data, & users. It provides services that enable different applications & services to communicate using common messaging frameworks such as JSON, REST, XML, SOAP, or any other web services & also it provides services that enable components written in multiple languages such as Java, C++, PHP & Python for communicational purposes.

express.json() is a method inbuilt in express to recognize the incoming Request Object as a JSON Object. This method is called as a middleware in your application using the code: app.use(express.json()).

![response-request](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Fetching_data/web-site-architechture@2x.png)

* Response object - It is based on sending instructions to the client browser.
* Request object - It is based on reading the data submitted by the client in which the data comes with the client

![routing-middleware](https://andrewlock.net/content/images/2019/endpoint_routing_banner.png)

Routing middleware is based on mapping a request URL path to some handler that generates a response. This is primarily used with the MVC middleware for mapping requests to controllers & actions, but it is used in other areas which includes functionality for the reverse process: generating URLs that will invoke a specific handler with a given set of parameters

![behavioral-testing](http://www.codekul.com/blog/wp-content/uploads/2018/03/What-is-Behavioral-Testing__-1280x720.png)

Behavioral testing (also known as black box testing) is the testing of external behavior of the program which can be applied in any program. The main aim of black box testing is based on the inputs & outputs. The black box used to get different types of Errors such as function missing, Usability, Performance, Concurrency & timing Problems, Initializing & terminating errors & so on.

![tdd](https://marsner.com/wp-content/uploads/test-driven-development-TDD.png)

It is a software engineering practice of writing unit tests before writing the production code which provides a structure to the coding process & as a result, it writes a code with a major purpose.

**Which 3 things had you heard about previously and now have better clarity on?**

Answer: Routing, application middleware & unit testing

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

Answer: Routing, application middleware & unit testing

**What are you most excited about trying to implement or see how it works?**

Answer: Everything

**Name 3 real world use cases where you’d want to change the request with custom middleware**

Answer: Application integration, data integration & Data oriented middleware.

**True or false: The route handler is middleware?**

Answer: False

**In what ways can a middleware function end the process and send data to the browser?**

Answer:The HTTP status will be 500 if there's errors occuring

**At what point in the request lifecycle can you “inject” middleware?**

Answer:It only has 3 extensions that injects the middleware

**What can cause express to error with “Request headers sent twice, cannot start a second response”**

Answer:It only happens if more than one response is sent to the client
