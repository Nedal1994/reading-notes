# Read02 Summary

![http methods](https://user-images.githubusercontent.com/4013025/48322141-cf7af680-e604-11e8-8a76-ae4d92a83793.png)

HTTP is based on defining a set of requesting methods which are desired to perform for a given resource. When it comes to API operations in terms of HTTP methods, its important to note that the HTTP protocol defines a number of methods that assign a semantic meaning to the request.

Here are some HTTP methods:

* GET - The GET method is based on requesting the resource's representation in which it can only receive the data. For a successful GET method, it returns HTTP status code 200 which indicate that the server received the data successfully, but if the resource is not found, then it would return 404 which is not found.

* POST - THe POST method is based on submitting an entity to the resource which can have side effects on the server sometimes. Like the GET method, the POST method can be successful if it does processing that returns HTTP status code 200 which include the result of the operation response body, but if its not successful, it will return HTTP status code 204 which indicates that it has no content.

* PUT - The PUT method replaces the representations of the resources with a request payload. The PUT method can be successful if it creates a new resource which returns HTTP code status 201, but if the method updates the resource, it will either return 200 (OK) or 204 (No content).

* DELETE - The DELETE method is based on adeleting the resources & for it to be successful, the web server must respond with HTTP status code 204 (No content) which means that the process is successsful, but if its not handled not only the body contains no details, but the resource will not exist which indicates that the web server returns HTTP 404 (Not found)

![rest](https://networkinterview.com/wp-content/uploads/2021/06/REST-DP.jpg)

The Roy Fielding State Transfer (REST) is an architectural approach for designing web services. It is based on building distributed systems which are based on hypermedia & REST is an independent protocol which is not tied with HTTP. The main purpose of REST is to use open standards without implementing API to which the client applications are looking for any specific implementation.

![rest api](https://www.astera.com/wp-content/uploads/2020/01/rest.png)

REST API is based on a method for 2 computers that communicate over HTTP which is similar to web browsers & servers. However, sharing the data between 2 or more systems is a very crucial requirement for software develpment. Based on the fact that REST APIs are designed around resources, it consists of many types of objects, data or service that can be accessed by the client in which the resource is considered as an identifier.

![soap api](https://mycodetips.com/wp-content/uploads/2019/12/SOAP_API.png)

SOAP API is based on a standard communication protocol system that permits processes using different operating systems like Linux & Windows to communicate via HTTP and its XML & they are designed to create, recover, update & delete data. It take the advantages of making web based protocols such as HTTP and its XML that are already operating the all operating systems that are why its developers can easily manipulate web services and get responses without caring about language and platforms at all.

* Web server - It is a software & hardware that uses HTTP & other protocols to respond to client requests made over the World Wide Web

* Express - It is a minimal & flexible Node.js web application framework that provides a robust set of features for web & mobile application

* Routing -  It is a mechanism where HTTP requests are routed to the code that handles them

* WRRC - It is based on how the data is exchanged between the server & client. There are two types of messages: requests sent by the client to trigger an action on the server, responses & the answer from the server

![cicd](https://www.parasoft.com/wp-content/uploads/2021/04/CICD_CICD.png)

CI & CD stand for continuous integration & continuous delivery/continuous deployment. CI is a modern software development practice in which incremental code changes are made frequently and reliably. Automated build-and-test steps triggered by CI ensure that code changes being merged into the repository are reliable. The code is then delivered quickly and seamlessly as a part of the CD process. It allows organizations to ship software quickly & efficiently which facilitates an effective process for getting products to market faster than ever before, continuously delivering code into production, & ensuring an ongoing flow of new features & bug fixes via the most efficient delivery method. 

![tdd](https://marsner.com/wp-content/uploads/test-driven-development-TDD.png)

It is a software engineering practice of writing unit tests before writing the production code which provides a structure to the coding process & as a result, it writes a code with a major purpose.