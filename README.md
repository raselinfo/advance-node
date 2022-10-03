# Advance NodeJS

## What is NodeJS

Node.js is an open-source server side runtime environment built on
Chrome's V8 JavaScript engine. It provides an event driven, non-blocking
(asynchronous) I/O and cross-platform runtime environment for building
highly scalable server-side applications using JavaScript.

Node. js is primarily used for non-blocking, event-driven servers, due to its single-threaded nature
<img src="https://thewebsmithsite.files.wordpress.com/2015/11/pngbase643f17317a5d7e7fe9.png"/>

## What does mean by Blocking and No-Blocking I/O

Blocking call waits for the I/O operation to complete before returning. Its results are returned synchronously. Nothing else in that process takes place during the waiting. In contrast, non-blocking call returns immediately without results and uses alternate means to check for completion.

A Non-Blocking server means that it is able to have multiple requests in progress at the same time by the same process or thread because it uses Non-Blocking I/O

## What is I/O

I/O (input/output), pronounced "eye-oh," describes any operation, program, or device that transfers data to or from a computer. Typical I/O devices are printers, hard disks, keyboards, and mouses.

input/output, I/O refers primarily to the program's interaction with the system's disk and network. Examples of I/O operations include reading/writing data from/to a disk, making HTTP requests, and talking to databases. They are very slow compared to accessing memory (RAM) or doing work on the CPU

# Why is Node JS good for IO?

In its most basic form Node. js is best suited for this type of computing. All I/O in Node. js is non-blocking and it allows other requests to be served while waiting for a particular read or write to complete

The Node. js project includes a JavaScript engine, event loop, and I / O layer. It is often referred to as a non-blocking web server. Note: “I/O” generally refers to the interaction between the system's disk and network and is supported by libuv

## What is callback

A callback is a function which is called when a task is completed, thus helps in preventing any kind of blocking and a callback function allows other code to run in the meantime. Callback is called when task get completed and is asynchronous equivalent for a function. Using Callback concept, Node.

## What does mean by Event Driven in Nodejs

An event-driven application is a computer program that is written to respond to actions generated by the user or the system. In a computing context, an event is any identifiable occurrence that has significance for system hardware or software.

**Event-driven programing:**
In computer programming, event-driven programming is a programming paradigm
in which the flow of the program is determined by events such as user actions
(mouse clicks, key presses), sensor outputs, or message passing from other
programs or threads

**Event-driven programming in node:**

- Node.js uses events heavily and it is also one of the reasons why
  Node.js is pretty fast compared to other similar technologies.
- As soon as Node starts its server, it simply initiates its variables,
  declares functions and then simply waits for the event to occur.

In an event-driven application, there is generally a main loop that
listens for events, and then triggers a callback function when one
of those events is detected.
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20211017211104/EDP1drawio-660x305.png"/>
<img src="https://s1.o7planning.com/en/11951/images/21212668.png"/>
<img src="https://i.stack.imgur.com/BTm1H.png"/>
<img src="https://i.ytimg.com/vi/sFdj0I_ul7k/maxresdefault.jpg"/>

## What is single thread and is nodejs single thread?
What is meant by single threaded?
"Single-threaded" means that we open a single connection and measure the speeds from that. "Multi-threaded" means that we're using multiple connections - usually anywhere from 3 to 8 - at the same time, and measure the total speed across them all.

Node JS Platform doesn't follow the Multi-Threaded Request/Response Stateless Model. It follows the Single-Threaded with Event Loop Model. Node JS Processing model mainly inspired by JavaScript Event-based model with JavaScript callback mechanism

Clients Send request to Web Server. Node JS Web Server internally maintains a Limited Thread pool to provide services to the Client Requests. Node JS Web Server receives those requests and places them into a Queue. It is known as “Event Queue”.
## What is v8 engine?

V8 is Google's open source high-performance JavaScript and WebAssembly engine, written in C++. It is used in Chrome and in Node. js, among others. It implements ECMAScript and WebAssembly, and runs on Windows 7 or later, macOS 10.12+, and Linux systems that use x64, IA-32, ARM, or MIPS processors.
  