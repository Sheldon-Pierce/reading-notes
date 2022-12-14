[Home](../README.md)

## JavaScript

JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles.

JavaScript's dynamic capabilities include runtime object construction, variable parameter lists, function variables, dynamic script creation (via eval), object introspection (via for...in and Object utilities), and source-code recovery (JavaScript functions store their source text and can be retrieved through toString()).

This section is dedicated to the JavaScript language itself, and not the parts that are specific to Web pages or other host environments. For information about APIs that are specific to Web pages, please see Web APIs and DOM.

The standards for JavaScript are the ECMAScript Language Specification (ECMA-262) and the ECMAScript Internationalization API specification (ECMA-402). As soon as one browser implements a feature, we try to document it. This means that cases where some proposals for new ECMAScript features have already been implemented in browsers, documentation and examples in MDN articles may use some of those new features. Most of the time, this happens between the stages 3 and 4, and is usually before the spec is officially published.[-1]

## Introduction to JavaScript - basic output

While learning about Node.js, JQuery, or Angular.js might be fun, I think it is important to have some background, and to know how to use plain JavaScript. This series of articles will provide an introduction to JavaScript.

Before we get to the syntax, first let's understand where can we run JavaScript.

Traditionally JavaScript was used inside web browsers such as Mozilla Firefox, Internet Explorer, Chrome, Opera, or Safari. The author would include some JavaScript code in the HTML page the user receives when she visits a web site. That JavaScript code would run in the browser (what we call "client side", as opposed to running on the web server which is called "server side").

In recent years people have started to put JavaScript code on the server as well. Probably the most well know environment to run JavaScript on the server is Node.js, but there are others. For example io.js which started as a Node.js fork.

We can distinguish 3 major parts of what we usually refer to as "JavaScript".

- The language itself. This is fairly standard among the various environments, both in the various browsers and in the various server-side environments.
- The DOM API - how the language can interact with the various parts of a web page while in the browser. While in this respect the various browsers are getting closer to each other they still differ. Several libraries, most prominently JQuery, is trying to provide a unified API.
- The server API (or just API) provided by Node.js or one of the other server-side systems.
In this series of articles we'll see all 3 major components.

Let's start with a few simple examples we can run in a browser. It is probably the easiest to get started this way, as these examples only require you to have a browser (and if you are reading this, then you probably have one), and a text editor.

## Embed or include

You can either embed the JavaScript code directly inside the HTML file, or you can put a line in the HTML file that will include the external JavaScript file. In most cases the latter is recommended, but for our first examples, in order to make the whole thing work in a single file, we'll embed the JavaScript code inside some HTML.

In order to do that we add the \<script> opening and \</script> closing tags. Between the two we write our JavaScript code.[-2]

## Prompt

The fist one is called prompt. It will show a pop-up window with the text provided as the first parameter and with a textbox the user can fill in. When the user presses OK, the value in the text box will be returned by the prompt() function. Then, in this example we use the document.write method to update the html with the text.

## Confirm

The other pop-up is not really an input method. It allows the developer to ask a Yes/No question. Calling the confirm() function will show a pop-up window with the provided texts and with two buttons. If the user presses OK the confirm() function will return true, if the user presses cancel or hits the ESC key, the function will return false.

Of course in order for this to make more sense you'll have to understand what true and false really mean and what this if - else construct does. If you have programming background then you probably already understand the code, and even if you don't have programming background you might figure out.

That code can basically be translated to the following English sentence:

If confirm returned true, print "Hello World", otherwise print "OK, I won't print it."

Or even better:

If the user presses OK when we asked "Shall I print Hello World?", then print "Hello World", otherwise print "OK, I won't print it."[-3]










## Things I want to know more about

[-1]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
[-2]: https://code-maven.com/introduction-to-javascript
[-3]:https://code-maven.com/javascript-input-with-prompt-and-confirm