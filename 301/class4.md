## What is a ‘Controlled Component’?
In HTML, form elements such as input, textarea, and select typically maintain their own state and update it based on user input.

We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.

With a controlled component, the input’s value is always driven by the React state. While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers.

1. The condition is what you’re actually testing. The result of your condition should be true or false or at least coerce to either boolean value.
2. A ? separates our conditional from our true value. Anything between the ? and the : is what is executed if the condition evaluates to true.
3. Finally a : colon. If your condition evaluates to false, any code after the colon is executed.

**Conditional rendering** in React works the same way conditions work in JavaScript. Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them.
