# Read11 Summary

![events](https://www.tutorialspoint.com/nodejs/images/event_loop.jpg)

Event-Driven Programming is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision. In this article we’re going to go over how Event-Driven Programming works and how we can make the best use of it in our Node.js projects. Most developers are introduced to concepts of Event-Driven Programming early on in their study of programming yet they might not fully realize it until a bit later. You’ll find that the concept is rather ubiquitous. Check any major framework or software out there and odds are you’ll find evidence of Event-Driven Programming.

![event-emitter](https://cdn-media-1.freecodecamp.org/images/plokwquvVbN4xa25kuk-QvYJ9b2ICqXWZ4Hb)

Node.js natively provides us with a useful module called EventEmitter that allows us to get started incorporating Event-Driven Programming in our project right away. Of course, creating our own version of EventEmitter wouldn’t be much of a challange, and in fact there are several modules published on npm such as EventEmitter2 and EventEmitter3 which promise a faster performance than the native EventEmitter. Those are both worth checking out if your project needs to run faster than EventEmitter will allow. They are both built to allow for syntax that is almost identical to what we’ll use for EventEmitter so learning one will make it easy to work with all of them.

**Removing Listeners**

There will likely come a time when you want to remove an event listener from an event. This could be for performance reasons (the event is no longer needed) or to avoid memory leaks (if an event listener references an object that is no longer needed, it won’t be able to be garbage-collected. This can lead to a build up of unnecessary objects). To remove event listeners in EventEmitter we can use the removeListener or removeAllListeners method. It’s important to note that in the EventEmitter that comes built-in with Node you must pass a reference to the exact function you wish to remove when using the removeListener method. This means wherever you wish to remove the event, you’ll need to make sure the function is able to be referenced from that place in your code. For this reason it is often best to name your event handling functions and declaring them before you register the event listener, as opposed to leaving them anonymous.

![event-driven-programming](https://www.technologyuk.net/computing/software-development/software-design/images/event_driven_02.gif)

Event-driven programming is a programming paradigm in which the flow of program execution is determined by events - for example a user action such as a mouse click, key press, or a message from the operating system or another program. An event-driven application is designed to detect events as they occur, and then deal with them using an appropriate event-handling procedure. The idea is an extension of interrupt-driven programming of the kind found in early command-line environments such as DOS, and in embedded systems (where the application is implemented as firmware).

![object-oriented-programming](https://miro.medium.com/max/2000/1*49bII3LtVCdF35f8Dg2Krw.png)

The Object Oriented approach promotes the idea that all behavior of an individual unit (or object) be handled from code within that unit. Using this approach, applications are built with many different units that all speak to and interact with each other.The combination of the Object Oriented and Event-driven programming paradigms. These two make for a very valuable combination in a wide variety of situations and I think it can be beneficial to understand and conceptualize