# Read12 Summary

**What is the benefit of transforming data into packets?**

It meets the demands of pervasive data-centric applications and services

**UDP is often referred to as a connectionless protocol. Why is this?**

Because there's no connection that needs to be established between the source & destination before you transmit data

**Can a socket server application have multiple socket connections?**

Yes it does

**Can a socket connection application be connected to multiple socket servers?**

Yes it does

**Can an application be both a socket server and a socket connection?**

 Yes

 | Vocabulary  | Definition  |
|---|---|
| Observer Pattern | A  software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.  |
| Listener | It is a procedure in JavaScript that waits for an event to occur |
| Event handler| It is a piece of code that will execute to respond to that event |
| Event driven programming| It is a programming paradigm in which the flow of program execution is determined by events - for example a user action such as a mouse click, key press, or a message from the operating system or another program|
| Event loop| It is a programming constructor or design pattern that waits for and dispatches events or messages in a program|
| Event queue| A repository where events from an application are held prior to being processed by a receiving program or system|
| Call stack| A stack data structure that stores information about the active subroutines of a computer program|
| Emit| An object/method which triggers an event as soon as some action takes place so as to pass the control to the parent function|
| Raise| A request by the developer to execute handlers that are defined for an event at a given time.|
| Subscribe|  A JavaScript object that defines the handlers for the notifications you receive.|

![osi model](https://miro.medium.com/max/1024/1*17Zz6v0HWIzgiOzQYmO6lA.jpeg)

The application layer is used by end-user software such as web browsers and email clients. It provides protocols that allow software to send and receive information and present meaningful data to users. A few examples of application layer protocols are the Hypertext Transfer Protocol (HTTP), File Transfer Protocol (FTP), Post Office Protocol (POP), Simple Mail Transfer Protocol (SMTP), and Domain Name System (DNS).

The presentation layer prepares data for the application layer. It defines how two devices should encode, encrypt, and compress data so it is received correctly on the other end. The presentation layer takes any data transmitted by the application layer and prepares it for transmission over the session layer.

The session layer creates communication channels, called sessions, between devices. It is responsible for opening sessions, ensuring they remain open and functional while data is being transferred, and closing them when communication ends. The session layer can also set checkpoints during a data transfer—if the session is interrupted, devices can resume data transfer from the last checkpoint.

The transport layer takes data transferred in the session layer and breaks it into “segments” on the transmitting end. It is responsible for reassembling the segments on the receiving end, turning it back into data that can be used by the session layer. The transport layer carries out flow control, sending data at a rate that matches the connection speed of the receiving device, and error control, checking if data was received incorrectly and if not, requesting it again.

The network layer has two main functions. One is breaking up segments into network packets, and reassembling the packets on the receiving end. The other is routing packets by discovering the best path across a physical network. The network layer uses network addresses (typically Internet Protocol addresses) to route packets to a destination node.

The data link layer establishes and terminates a connection between two physically-connected nodes on a network. It breaks up packets into frames and sends them from source to destination. This layer is composed of two parts—Logical Link Control (LLC), which identifies network protocols, performs error checking and synchronizes frames, and Media Access Control (MAC) which uses MAC addresses to connect devices and define permissions to transmit and receive data.

The physical layer is responsible for the physical cable or wireless connection between network nodes. It defines the connector, the electrical cable or wireless technology connecting the devices, and is responsible for transmission of the raw data, which is simply a series of 0s and 1s, while taking care of bit rate control.

![tcp handshake](https://s3.ap-south-1.amazonaws.com/afteracademy-server-uploads/what-is-a-tcp-3-way-handshake-process-three-way-handshaking-establishing-connection-6a724e77ba96e241.jpg)

The 3-Way Handshake process is the defined set of steps that takes place in the TCP for creating a secure and reliable communication link and also closing it. Actually, TCP uses the 3-way handshake process to establish a connection between two devices before transmitting the data. After the establishment of the connection, the data transfer takes place between the devices. After which the connection needs to be terminated, which is also done by using the 3-way handshake process. The secure and reliable connection is established to reserve the CPU, buffer, and bandwidth of the devices to communicate properly. Thus, it is a must to free these resources by terminating the connection after data transmission. Hence, the TCP 3-way handshake process can be used to establish and terminate connections in the network in a secure way.

![websocket](https://upload.wikimedia.org/wikipedia/commons/1/10/Websocket_connection.png)

WebSocket is a communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection; WebSocket remains open all the time, so they allow real-time data transfer. When clients trigger the request to the server, it does not close the connection on receiving the response; it rather persists and waits for the Client or server to terminate the request.

![socketio](https://ik.imagekit.io/ably/ghost/prod/2021/03/socket-io-logo.jpeg?tr=w-1520)

Socket.IO is a JavaScript library for real-time web applications. It enables real-time, bi-directional communication between web clients and servers. It has two parts − a client-side library that runs in the browser, and a server-side library for node.js. Both components have an identical API.