# Trees

## Terminology

- Node = a single component of the tree consisting of a value and references to the components children.
- Root = the top level node.  
- Left = a reference to the rigth node being looked at.  
- Right = A reference to the right node of the node being looked at.  

## Traversals  

### Depth First

A traversal going down the tree first(in-order, pre-order, post-order).

- Pre-order
Root Left Right.  

- Post-order  
Left Right Root.  

- In-order
Left Root Right.  

### Breadth First

A traversal going to each level of the tree(Uses queue).

### Binary Tree vs K-ary  

- Binary trees have only two children per parent.  
- K-ary trees can have multiple children per parent.  
- Binary trees can be filled using a top down strategy placing the node in the next available spot.  

### Binary Search Trees

- Nodes smaller than root are placeed below to the left.
- Nodes with values larger are placed to the right.  
- Searching is quick.
- A balanced tree shpuld have log(n) time complexity.  