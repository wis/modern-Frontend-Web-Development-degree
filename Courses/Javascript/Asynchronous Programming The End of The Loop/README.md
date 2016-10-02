https://egghead.io/courses/mastering-asynchronous-programming-the-end-of-the-loop
## Asynchronous Programming: The End of The Loop
### 59 minutes

Learning how to build and manage asynchronous programs is perhaps the most important part of becoming an effective JavaScript programmer. [Unlike most programming languages, JavaScript is single-threaded. [As a result, JavaScript programs must use async APIs to stay responsive to user input while performing long-running tasks like server requests and animations. [You can't get very far in a JavaScript program without running across an asynchronous API.

Async programming may seem daunting. [How can we write programs that accept user input, run animations, and send server requests over the same period of time? How do we keep the code clear and concise? How do we gracefully propagate and handle asynchronous errors? How can we avoid memory leaks caused by dangling event handlers? JavaScript's loops and try/catch keywords are no help - they only work on synchronous functions.

Here's the good news: Asynchronous programming is much easier than it seems. [The key is to think differently about events. [It is possible to build most asynchronous programs using a handful of simple functions. [We will learn why most JavaScript developers approach asynchronous programming the wrong way, and how to avoid these common mistakes. [By the end of these lessons you will know the tools, concepts, and libraries required to be an asynchronous programming ninja!

In this section, we'll learn the first secret to mastering asynchronous programming: programming without loops. [JavaScript's loops can only run synchronously, and cannot be used to repeat asynchronous functions. [As a result, in order to master asynchronous programming we must first master programming without loops. [In this series we will learn how to program Arrays without loops using just a few simple functions.

	1	04:03	foreach method
	2	03:02	map method
	3	04:42	filter method
	4	03:05	chaining the array map and filter methods
	5	04:17	create an array concatall method
	6	11:59	introducing the observable
	7	03:45	using the map method with observable
	8	12:35	simple drag and drop with observables
	9	11:58	advanced flattening