# Read08 Summary

![rest](https://networkinterview.com/wp-content/uploads/2021/06/REST-DP.jpg)

The Roy Fielding State Transfer (REST) is an architectural approach for designing web services. It is based on building distributed systems which are based on hypermedia & REST is an independent protocol which is not tied with HTTP. The main purpose of REST is to use open standards without implementing API to which the client applications are looking for any specific implementation.

![rest api](https://www.astera.com/wp-content/uploads/2020/01/rest.png)

REST API is based on a method for 2 computers that communicate over HTTP which is similar to web browsers & servers. However, sharing the data between 2 or more systems is a very crucial requirement for software develpment. Based on the fact that REST APIs are designed around resources, it consists of many types of objects, data or service that can be accessed by the client in which the resource is considered as an identifier.

![http methods](https://user-images.githubusercontent.com/4013025/48322141-cf7af680-e604-11e8-8a76-ae4d92a83793.png)

HTTP is based on defining a set of requesting methods which are desired to perform for a given resource. When it comes to API operations in terms of HTTP methods, its important to note that the HTTP protocol defines a number of methods that assign a semantic meaning to the request.

Here are some HTTP methods:

* GET - The GET method is based on requesting the resource's representation in which it can only receive the data. For a successful GET method, it returns HTTP status code 200 which indicate that the server received the data successfully, but if the resource is not found, then it would return 404 which is not found.

* POST - THe POST method is based on submitting an entity to the resource which can have side effects on the server sometimes. Like the GET method, the POST method can be successful if it does processing that returns HTTP status code 200 which include the result of the operation response body, but if its not successful, it will return HTTP status code 204 which indicates that it has no content.

* PUT - The PUT method replaces the representations of the resources with a request payload. The PUT method can be successful if it creates a new resource which returns HTTP code status 201, but if the method updates the resource, it will either return 200 (OK) or 204 (No content).

* DELETE - The DELETE method is based on adeleting the resources & for it to be successful, the web server must respond with HTTP status code 204 (No content) which means that the process is successsful, but if its not handled not only the body contains no details, but the resource will not exist which indicates that the web server returns HTTP 404 (Not found)

![regExr](https://regexr.com/assets/card.png)

RegExr is an online tool that allow users to learn & experience Regular Expressions (RegEx/RegExp). It supports Javascript, Python, Java, PHP & many other programming languages.
