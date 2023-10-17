# Nodejs Interview Questions & Answers

### Table of Contents


#### Q. What is Nodejs?
  
  - `Nodejs` is an open-source, cross-platform Javascript runtime enviroment.


#### Q. What is Chrome's V8 engine?

  - `V8` is Javascript Engine that converts Javascript code into machine code.
  - That means `V8` can execute Javascript code either within browser and in server-side.


#### Q. What is modules?

  - A `module` is an encapsulated and reusable chunk of code that has its own context.


#### Q. What is CommonJS?

  - `CommonJs` is a set of standards used to implement Javascript modules.


#### Q. What is module caching?

  - When a module is imported for the first time, it's cached in memory. 
  In the next time it's imported, it returns from the cache.


#### Q. Name some build-in modules?
  - fs
  - stream
  - http
  - path
  - events


#### Q. How to use watch mode?

  ```nodejs
    node --watch index
  ```


#### Q. What is Callback?

  - A `callback` is a function passed as argument to another function. 


#### Q. What is Promise?
  - A `promise` is an object that represents eventual completion (or failure) of async operation and its returning value.


#### Q. What is Promise.all?
  - `promise.all()` takes an iterable of promises as the input and returns a single Promise.
  - It returns promise fulfills when all of the input's promises fulfill.
  - Otherwise, it rejects when any of the input's promises rejects, with the first rejection reason.


#### Q. What is Promise.allSettled?

  - It has the same implementation with Promise.all
  - But it always wait for all of the input's promises settle.

#### Q. What is EventEmitter?

  - Nodejs allows us to create and handle custom events by using `events module`.
  - `Events module` includes `EventEmitter` class that is used to raise and handle custom events.


#### Q. What is File module?

  - `File module` allows us to work with the file system on computer.


#### Q. What is the difference between readFileSync and readFile?

  - `readFileSync` is used to read a file synchronously, it blocks main thread.
  - `readFile` is used to read a file asynchronously and doens't block main thread.
  - we can also use `fs Promise` to read the file asynchronously.


#### Q. What are Streams?

  - A `stream` is a sequence of data that is being moved from one point to anther over time.


#### Q. Name the types of streams?

  - `Readable stream` can read data from particular data source.
  - `Writable stream` is used to write data from data source to a specific destination.
  - `Duplex stream` that are both Readable and Writable. Ex: `Socket`.
  - `Transform stream` is a Duplex stream where the output is computed by some way from the input.
    Example include `zlib` and `crypto` streams to compress, encrypt or decrypt data.


#### Q. What is Pipe?
  - Pipe method is used to join or pipe two streams together.
  Basically, this method is called by a readable stream to pass data to write onto a writable stream.


#### Q. What is HTTP?
  - HTTP stands for Hypertext Transfer Protocol.
  - It defines a format for clients and servers to speak to each other.
  - The client sends an HTTP request to the server, then the server responds with an HTTP response.


#### Q. Is Javascript a single-threaded, block, synchronous language?

  - Yes.


#### Q. What are Threads?
  
  - A `thread` is a smallest sequence of intructions within a process.
  - It can be executed independently with other code.
  - It uses the same resources of the process to which it belongs.


#### Q. What is Process?
  
  - A `process` is an instance of a program.
  - It's being executed by one or many `threads`.
  - It has its own resources such as memory space, files, callstack, register and counters. (and something else)
  - By default, a `process` is a `single-threaded application`.


#### Q. What is Libuv?

  - `Libuv` is a open-source cross-platform library written in C language.
  - `Libuv` handles asynchronous non-blocking operations.
  - It uses `Event loop` and `Thread pool`.


#### Q. What is Thread pool?

  - A `thread pool` is a collection of threads that are available to perform multiple tasks.
  - `Libuv` uses `Thread pool` to handle asynchronous operations to improve the performance of application.
  - Increasing `Thread pool size` is limited by numer of CPU cores. 


#### Q. How does `Libuv` handle `http.request`?

  - A `http.request` is a network I/O operation, it's not the CPU bound operation.
  - It doesn't use `Thread pool`.
  - `Libuv` use native async mechanisms to handle `http.request`.
  That means `Libuv` delegates the work to the OS kernel.
  It also polls the kernel and see when the operation is completed.


#### Q. What is Event Loop?

  - `Event loop` is a C program and is a part of `Libuv`.
  - `Event loop` handles asynchronous callbacks.
  - `Event loop` iterates over the `events queue`.
  And it also polls the `call stack` and sees when the `call stack` is empty,
  `Event loop` picks the first `callback` in `events queue` and pushes it to the `call stack`
  and then executes it.


#### Q. What is Cluster module?

  - The `cluster module` enables the creation of child processes (also called workers) that run simultaneously.

#### Q. What is the difference between `spawn()` and `fork()`?
  
  - `fork` is used to create child processes that copy the parent process.
  - `spawn` is used to create independent and distict logical child processes.
  