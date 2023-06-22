# React Hooks

## Thinking in React 

Summarize the five steps of thinking in react.

- break up the UI in components, build a static version, represent UI state, identify where state shouls go and add adata flow.  

## State: A Component’s Memory

What is one reason a local variable isn’t sufficient for managing a React component?

- React re-renders componewnts from scratch and local variables to not persist on those re-renders and will not trigger a re-render if changed.  

What is the argument to the useState hook, and what are the two parts of its return array?

- The useState hook requires the intial value of the state and returns an array with the state vaiable and a set state function which triggers the component to re-render

How can Component A access state from Component B?

- If component A passes state down to component B, Component B can lift that state up to component A with set state function.   
