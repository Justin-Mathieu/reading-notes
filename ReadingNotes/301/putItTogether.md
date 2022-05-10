# Putting it all Together Reading Notes

## React Docs

1.What is the single responsibility principle and how does it apply to components?

- A component should do one thing. or be made into smaller components.

1.What does it mean to build a ‘static’ version of your application?

- A static vewrsion is a version that takes the data and renders but is not wired up.

1.Once you have a static application, what do you need to add?

- Add state.

1.What are the three questions you can ask to determine if something is state?

-Is it passed as props?, Does it change?, is it based off of other state or props?

1.How can you identify where state needs to live?

- The component that is highest on the chain that deals with the state.

## High Order Functions

1. What is a “higher-order function”?

- Higher order functions are  functions that take in or return other functions.

1. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

- LIne 2 is returning another function.

1. Explain how either map or reduce operates, with regards to higher-order functions.

- reduce and map can take in functions as arguments therefore can become higherorder functions.
