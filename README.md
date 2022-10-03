# Advance NodeJS

## What is NodeJS

Node.js is an open-source server side runtime environment built on
Chrome's V8 JavaScript engine. It provides an event driven, non-blocking
(asynchronous) I/O and cross-platform runtime environment for building
highly scalable server-side applications using JavaScript.

Node. js is primarily used for non-blocking, event-driven servers, due to its single-threaded nature

## What does mean by Blocking and No-Blocking I/O
Blocking call waits for the I/O operation to complete before returning. Its results are returned synchronously. Nothing else in that process takes place during the waiting. In contrast, non-blocking call returns immediately without results and uses alternate means to check for completion.
A Non-Blocking server means that it is able to have multiple requests in progress at the same time by the same process or thread because it uses Non-Blocking I/O

## What is I/O
input/output, I/O refers primarily to the program's interaction with the system's disk and network. Examples of I/O operations include reading/writing data from/to a disk, making HTTP requests, and talking to databases. They are very slow compared to accessing memory (RAM) or doing work on the CPU

# Why is Node JS good for IO?
In its most basic form Node. js is best suited for this type of computing. All I/O in Node. js is non-blocking and it allows other requests to be served while waiting for a particular read or write to complete
## What is v8 engine?

V8 is Google's open source high-performance JavaScript and WebAssembly engine, written in C++. It is used in Chrome and in Node. js, among others. It implements ECMAScript and WebAssembly, and runs on Windows 7 or later, macOS 10.12+, and Linux systems that use x64, IA-32, ARM, or MIPS processors.
