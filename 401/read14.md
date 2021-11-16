# Read14 Summary

![sns](https://d1.awsstatic.com/diagrams/Product-page-diagram-Amazon-SNS_event-driven-SNS-compute%402X_.4b9c0a75aa40bda9cdb12f0176930a12da2872bf.png)

Amazon Simple Notification Service (Amazon SNS) is a web service that makes it easy to set up, operate, and send notifications from the cloud. It provides developers with a highly scalable, flexible, and cost-effective capability to publish messages from an application and immediately deliver them to subscribers or other applications. It is designed to make web-scale computing easier for developers. Amazon SNS follows the “publish-subscribe” (pub-sub) messaging paradigm, with notifications being delivered to clients using a “push” mechanism that eliminates the need to periodically check or “poll” for new information and updates. With simple APIs requiring minimal up-front development effort, no maintenance or management overhead and pay-as-you-go pricing, Amazon SNS gives developers an easy mechanism to incorporate a powerful notification system with their applications.

![sqs](https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/images/code-samples-sqs.png)

Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. SQS eliminates the complexity and overhead associated with managing and operating message-oriented middleware, and empowers developers to focus on differentiating work. Using SQS, you can send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available. Get started with SQS in minutes using the AWS console, Command Line Interface or SDK of your choice, and three simple commands. SQS offers two types of message queues. Standard queues offer maximum throughput, best-effort ordering, and at-least-once delivery. SQS FIFO queues are designed to guarantee that messages are processed exactly once, in the exact order that they are sent.

![fifo](https://www.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-Queue-Illustration.png)

* It means that the first item added in the stack will be the last item popped out of the stack
* It means that the first item in the queue will be the first item out of the queue
*  The new element is inserted below the existing element, So that the oldest element can be at the top and taken out first.
* The new element is inserted above the existing element, So that the newest element can be at the top and taken out first.
* The First element to be entered in this approach, gets out First
*  It is used as an operating system algorithm, which gives every process CPU time in the order they arrive
* The data structure that implements FIFO is Queue.