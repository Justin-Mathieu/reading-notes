# Passing Functions as Props

## React Docs -Lists and Keys

1. What does .map() return?

- .map returns an array.

1. If I want to loop through an array and display each value in JSX, how do I do that in React?

- Embed the the expresion in the jsx using curly braces.

1. Each list item needs a unique ____.

- Key.

1. What is the purpose of a key?

- To give each list item a unique identifier.

## The spread Operator

1. What is the spread operator?

- The spread operatoris the three dots that are used to expand an object.

1. List 4 things that the spread operator can do.

- The spread operator can add the contents of an array,combine objects,using math functions and add a list item.

1. Give an example of using the spread operator to combine two arrays.

- Const thing = [...arr1, ...arr2];

1. Give an example of using the spread operator to add a new item to an array.

- const thing = [a, b, c, ...item]

1. Give an example of using the spread operator to combine two objects into one.

- Const thing = {...obj1, ...obj2};

## Passing functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?

- Creaate a function that will do the thing you are trying to change.

1. In your own words, what does the increment function do?

- The function maps through the arr ay and checks the name property to the name argument and updates the count that is then sett in state.

1. How can you pass a method from a parent component into a child component?

- You can pass the function down as a prop.

1. How does the child component invoke a method that was passed to it from a parent component?

- Either with an anonymous arrow function or with a helper function using "this.props".
