# Linked List Implementation

## Linked List

- A linked list is a series of nodes each pointing to the next one in the list.
- A singly linked list is a list that one has one reference to the next item.
- A doubly linked list is a list that has a reference to the node before and the node after.
- Nodes are the items in the list.  
- Next is the property that points to the nexrt node.
- The head is the start of the list.
- Current is the node being looked at currently.

### Traversing a linked list

To Traverse a linked list a while loop will be needed to iterate over the list since for each and a for loop can not be used. A counter or current value is needed to keep track of the itteration.

### Adding a Node

To add an ode we need to create the node and reassign it to the head and assign the reference to the old head.

### Adding Inside of a Linked List

To insert a node into a linked list we would need to trafverse the list and find where we need to isert the node. Then  create the node and reassign the next properties to the appropriate nodes.  

### Printing Nodes  

To print out nodes ee would traverse the node but in the while loop print the current node.  

## What is a Linked List Anyway

- Linear data structure/ has an order.  
- Must be traversed sequentially.  
- Linked lists use less memory than arrays
- Arrays use larger chunks of memory to store the chunk of infoermation as aopposed to linked lists that store the data as needed(not in chunks).
- Arrays are static(they can not grow or shrink in memory).
- Linked lists are dynamic(they ca grow or shrink in memory).
- Circular lists have the last node pointing to the fist node in the list.  

- O(1) constant time input size does not matter will take the same time  and space regardless.
- O(n) linear as input grows so does space and time.  
- O(n^2) grows eponentially as the input grows.
