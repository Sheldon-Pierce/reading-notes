
# Controlled Components

In HTML, form elements such as </input>, </textarea>, and </select> typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.

We should update state with their responses as soon as they enter them. So that state is always kept current with the current user using the form.

By setting the state with a function that takes in information when the event is submitted.

# The Conditional (Ternary) Operator

We would use this to shorten our if statements into one line of code with the conditional operator. 

let value = (x===y) ? true : false

## Things I want to know more about