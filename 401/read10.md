# Read10 Summary

![stacks & queues](https://res.cloudinary.com/practicaldev/image/fetch/s--BgQwtlaT--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://cdn-images-1.medium.com/max/1600/1%2AxSRTv4g2tofWQktkUwoRog.png)

Stacks are data structures that follow the “last-in-first-out” or “LIFO” paradigm. We can think of them like a stack of books. In order to retrieve the third book in the stack, we have to take the fifth book off first, then the fourth book, until we retrieve the third book.JavaScript doesn’t provide a native stack data structure, so we have to build our own with an array and a closure or a class.Stacks allow for constant-time adding and removing of an item. This is due to the fact that we don’t need to shift items around to add and remove them from the stack.Stacks, unfortunately, don’t offer constant-time access to the nth item in the stack, unlike an array. This means it can possible take O(n) where n is the number of elements in the stack, time to retrieve an item.

 Here are some of the stack methods:

* pop(): Remove the top item from the stack
* push(item): Add an item to the top of the stack
* peek(): Return the item at the top of the stack
* isEmpty(): Returns true if the stack is empty

A queue is a linear structure of sequential and ordered elements, similar to a stack, with a difference that it works based on the principle of first in first out (FIFO). Queues are very similar to linked lists and are typically used in breadth-first searches or when implementing a cache. Queues are much harder to update when adding and removing nodes.

 Here are some of the queues methods:

* enqueue(item): Remove the top item from the queue
* dequeue(): Add an item to the top of the queue
* peek(): Return the item at the top of the queue
* isEmpty(): Returns true if the queue is empty

![fifo lifo](https://cdn.wallstreetmojo.com/wp-content/uploads/2016/11/FIFO-vs-LIFO.jpg)

| FIFO (First in First out)  | LIFO  (Last in First out)|
|---|---|
| It means that the first item added in the stack will be the last item popped out of the stack. | It means that the last item added to the stack will be the first item popped out of the stack.|
| It means that the first item in the queue will be the first item out of the queue. | It means that the last item in the queue will be the last item out of the queue.|
|  The new element is inserted below the existing element, So that the oldest element can be at the top and taken out first. | The new element is inserted above the existing element, So that the newest element can be at the top and taken out first.|
|  The First element to be entered in this approach, gets out First.| The First element to be entered in this approach, gets out Last.|
|  It is used as an operating system algorithm, which gives every process CPU time in the order they arrive| It is used as a queuing theory that refers to the way items are stored in types of data structures.|
|  The data structure that implements FIFO is Queue.| The data structure that implements LIFO is Stack.|
