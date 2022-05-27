# Functional Programming

## Functional Programming Concepts

What is functional programming?

- Building and structure of programs that use computation and avoid changing state.

What is a pure function and how do we know if something is a pure function?

- Deterministisc, no side effects.

What are the benefits of a pure function?

- Not using global variables so if things are changed unintentionally the funv=ction will remain the same.

What is immutability?

- Something that can not change.

What is Referential transparency?

- The combination of pure functions and immutable data creates referential transparency.

## Modules and Require

What is a module?

- Separate files that handle certain thing to help keep the code organized.

What does the word ‘require’ do?

- Imports the file that needs to be used.

How do we bring another module into the file the we are working in?

- Export the module and import(require) it in to the file it is used.
require(./file/path/here)

What do we have to do to make a module available?

-module.exports = function name here
