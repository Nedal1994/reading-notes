# Read13 Summary

**What does it mean that web sockets are bidirectional? Why is this useful?**

WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates
asynchronously, without requiring the client to submit a request each time. In the context of networked AV and control
systems, this allows devices to send and receive continuous streams of data to and from any point on the network.

**Does socket.io use HTTP? Why?**

Yes. Because it requirse an http server for the initial upgrade handshake

**What happens when a client emits an event?**

If the client emits an event, it alerts & creates events that are passing from one client to another

**What happens when a server emits an event?**

If the server emits an event, it uses a feature called rooms which are arbitrary channels that sockets can join and leave. It can be used to broadcast events to a subset of clients

**What happens if a client “misses” an event ?**

The messages are ignored

![message-queues](https://www.cloudamqp.com/img/blog/thumb-mq.jpg)

A message queue is a queue of messages sent between applications which  includes a sequence of work objects that are waiting to be processed.

![rooms](https://socket.io/images/rooms.png)

Rooms are arbitrary channels that sockets can join and leave. It can be used to broadcast events to a subset of clients. The rooms can be used to call *join* to subscribe the socket to a given channel & simply use *to* or *in* when broadcasting or emitting several rooms & events.

![namespaces](https://socket.io/assets/images/namespaces-088745a8a8882118740f50b6b1232588.png)

A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection which is also known as "multiplexing". Namespaces are used to separate server logic over a single shared connection. A common use may be to separate admin concerns from those of regular users.