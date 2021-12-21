# Read38 Summary

![thunk](https://miro.medium.com/max/799/0*l66us_4-3WiL6af9.png)

Thunk is a programming concept where a function is used to delay the evaluation/calculation of an operation. Redux Thunk is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store’s dispatch method, which is then used to dispatch regular synchronous actions inside the function’s body once the asynchronous operations have been completed. The most common use case for Redux Thunk is for communicating asynchronously with an external API to retrieve or save data. Redux Thunk makes it easy to dispatch actions that follow the lifecycle of a request to an external API.