# React and Forms

## React docs

1. What is a ‘Controlled Component’?

- An input element whose state is controlled by react.

1. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

- We would want save the input on the submit beacuse then it would render whern are finisghed typing as opposed to with each keystroke.

1. How do we target what the user is entering if we have an event handler on an input field?

- This.state.value. and event.target.value

## The Conditional Ternary

1. Why would we use a ternary operator?

- If a certain block of code needs to run when a condition is met similar to an if statement.

1. Rewrite the following statement using a ternary statement: if(x===y){
  console.log(true);
} else {
  console.log(false);
}

- ((x === y) ? 'true' : 'false');
