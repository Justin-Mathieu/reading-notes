# Adveanced State with Reducers

## Extracting State Logic into a Reducer

What is the motivation for adding a reducer?  

- To consolidate state maangement into a single function.  

What are actions in the context of a reducer? How are they different than setting state directly?  

- Actions are relaying what the user did inorder to update the state based on the event handler for that specific action.  

What common list operation is useReduce named for, and why?  

- UseReduce is named after the reduce array function that creates a single arrray out of many. The useReducer function is used to create a single function out of the many event handlers and state updates.  

When should you switch from useState to useReducer?  

- When there are a lot of states and event handlers to keep track of, the useReducer function can help to simplify that logic.  
