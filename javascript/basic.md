# Basic questions about JavaScript

## **What is JavaScript?**

Basically,  JavaScript is a single-threaded and single concurrent programming language which means it can handle one task at a time. It’s a scripting language for the web. And, It is an interpreted language, which means it does not need a compiler to translate its code like other programming languages like C or C++.

JavaScript controls the dynamic elements of web pages. It works in web browsers and, more recently on web servers as well. Meaning that the server works in much the same way, waiting in a loop for a network request, and accepting more incoming requests while the first one is being handled.

## **How does it work?**

JavaScript is what is known as a client-side script. Most web apps, such as a search engine, work because of an interaction between the user device (e.g. computer, phone, or tablet) and a remote server. The software on the remote server sends information to the client (i.e. the user’s machine) and the software on the client-side reads the information and renders a Web page on the screen.

A client-side script is a programming language that performs its tasks entirely on the client’s machine and does not need to interact with the server to function. For instance, if you have a webpage loaded on your computer and your internet service provider goes down you’re still able to interact with the web pages already loaded on your browser. You will now, however, be able to navigate to new web pages or access any data located remotely.

JavaScript is asynchronous by nature, meaning it is designed to ensure non-blocking code execution. Non-blocking code do not prevent the execution of another piece of code. Meaning that it is able to communicate with the server in the background without interrupting the user interaction taking place in the foreground

For example. Today, search engines almost all have an autocomplete function. The user begins typing a word into the search box and a list of suggestions appears below. The experience is seamless. The suggestions appear without reloading the page.

In the background, as the user types the letters in the search box, JavaScript reads and sends them to a remote server and the server sends suggestions back

![google suggestions](https://i.imgur.com/gQi11xY.gif)

> The software on the server-side analyzes the words and runs algorithms to anticipate the user's search term. Such programs are diabolically large and complex. But the JavaScript on the client-side is as simple and small as possible to ensure fast interactions for the user.

## **JavaScript on the browser**

JavaScript script happens on the browser, which in reality is quite a complicated piece of software with a large number of lines of code. Two of the most important parts of it are the JavaScript engine and the rendering engine.

In Google Chrome, [Blink](https://docs.google.com/presentation/d/1boPxbgNrTU0ddsc144rcXayGA_WF53k96imRH8Mp34Y/edit#slide=id.g60f92a5151_40_0) is the rendering engine that is responsible for the whole rendering pipeline including DOM trees, styles, events, and V8 integration. It parses the DOM tree, resolves styles, and determines the visual geometry of all the elements. While continually monitoring dynamic changes via animation frames, Blink paints the content on your screen.

And, the JavaScript in chrome is the V8 engine. It is used inside Chrome and Node.js. It is in charge of executing the JavaScript code.

The JavaScript engine translates source code into machine code that allows a computer to perform specific tasks at the hardware level. It is composed of a `call stack` and a `memory heap`. A `call stack` is where our code is actually executed, using `execution context`. A `heap` is an unstructured memory pool that stores all the objects that our application needs.
