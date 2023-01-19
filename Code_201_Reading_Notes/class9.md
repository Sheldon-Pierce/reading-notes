[Home](../README.md)

## HTML Forms

Web forms are one of the main points of interaction between a user and a website or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage (see Sending form data later in the module), or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).

Before starting to code, it's always better to step back and take the time to think about your form. Designing a quick mockup will help you to define the right set of data you want to ask your user to enter. From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.

The \<form> element - This element formally defines a form. It's a container element like a <section> or <footer> element, but specifically for containing forms; it also supports some specific attributes to configure the way the form behaves. All of its attributes are optional, but it's standard practice to always set at least the action and method attributes

The \<label>, \<input>, and \<textarea> elements - Our contact form is not complex: the data entry portion contains three text fields, each with a corresponding <label>:

- The input field for the name is a single-line text field.
- The input field for the email is an input of type email: a single-line text field that accepts only email addresses.
- The input field for the message is a \<textarea>; a multiline text field.

The \<button> element - The markup for our form is almost complete; we just need to add a button to allow the user to send, or "submit", their data once they have filled out the form. This is done by using the \<button> element; add the following just above the closing \</ul> tag:

## Events

Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them.

For example, if the user clicks a button on a webpage, you might want to react to that action by displaying an information box. In this article, we discuss some important concepts surrounding events, and look at how they work in browsers. This won't be an exhaustive study; just what you need to know at this stage.

### Add Event Listener

Objects that can fire events have an addEventListener() method, that takes at least two arguments: the name of the event and a function to handle the event. So we call the button's addEventListener() method, passing in.

### Event Object
 
Sometimes, inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. This is called the event object, and it is automatically passed to event handlers to provide extra features and information