# Context

## Choosing the State Structure

Summarize the five principles for structuring state.  

- Group Related State  
  - Multiple states variables that are often updated together can be rolleed into one.  
- Contradictions  
  - Avoid state that contrdicts other state variables.  
- Redundant State  
  - Dont do things that can be handled without using state.  
- Dulicating state  
  - Dont use the same data in multiple state varables.  
- Nested State  
  - Avoid nesting state it is hard to update.  

## Passing State Deeply with Context

What problem do Contexts aim to solve?

- Context is used to make passing props to multiple componentrs easier by giving all components below access to the data.  

What is one technique to try before useContext?

- You could pass and lift state or pass props. Depending on how many components you have and what data they need context could make this easier.  

What hook complements useContext for complex applications?

- UseReducer compliments useContext both aim to simplify state management and can be use together.  
