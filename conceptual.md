### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?

React is a popular JavaScript library for building user interfaces, particulary for single-page applications where responsive and dynamic user experience is essential. React is also used on large-scale applications. Considering reacts component base structure, it helps manage large applications more efficiently. 


- What is Babel?

Babel is a tool that allows developers to use latest JavaScript features on old browsers. It converts JavaScript code written with new features into older versions so that it can run in a wider range of browsers.


- What is JSX?

JSX is stands for JavaScript XML. Its a syntax for JavaScript the allows you write HTML-like structures within your JavaScript code.  JSX makes it easier to write and understand your React components. JSX also allows you to describe what your UI should look like, rather than how to create it.  




- How is a Component created in React?
 
 First you should make sure you have imported React: import React from 'react';
Next create a fucntion definition to define the component as a simple javaScript function.
Then return JSX to descibe the component's UI structure.
Finally, export the component so that it can be used in the other parts of your application.



- What are some difference between state and props?

The main difference between state and props is how the are manged, what data they hold, and how they affect a component output. 

Props are passed to a component, while state is managed within the component.

Props are immutable and cannot be changed within the component, while state is mutable and can be updated based on user actons or other events.

Props allow data to flow from parent to child components, while state is used to handle data that changes over time within a component.



- What does "downward data flow" refer to in React?

Downward data flow also know as undirectional data flow, refers to the principle that data flows in one direction, from parent components to child components.




- What is a controlled component?

A controlled component is a form element whose value is managed by Reacts state.



- What is an uncontrolled component?

A uncontrolled component is a form input that manages its own stae directly through DOM, rather than being controlled by the React component's state.




- What is the purpose of the `key` prop when rendering a list of components?

The `key` prop is used to provide a unique identifier for each item in the list, allowing React to effciently track changes, additions, or removals within the list and updates the DOM accordingly.



- Why is using an array index a poor choice for a `key` prop when rendering a list of components?

Using an array is often discourage because it can lead to performance and UI bugs. When items are added or remo0ved from the list, indexes are shifted and React will not recognize the shift and may re-render the wrong components or lose the association between components and their data.



- Describe useEffect.  What use cases is it used for in React components?

useEffect is a hook that allows you to perform side effects in functional components. Side effects are actions that interact with the outside world including data fetching, DOM manipulation, subscriptions, and timers.




- What does useRef do?  Does a change to a ref value cause a rerender of a component?

useRef allows you to persist values between renders. It can be used to store mutable a value that does not cause a re-render when updated. It can be used to access a DOM element directly.



- When would you use a ref? When wouldn't you use one?

You should use a ref when you need to directly access a DOM element for imperative actions like focusing, scrolling, or measuring.  You should avoid using a ref when you can achieve the desired functionality declaratively using state or props. Onlyo use a ref when absolutely necessary.



- What is a custom hook in React? When would you want to write one?

Custom hooks are a mechanism to reuse stateful logic, but everytime you use a custom Hook, all state and effects inside of it are fully isolated.
