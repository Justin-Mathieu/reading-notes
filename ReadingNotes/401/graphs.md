# Graphs 

- Non linear data structure.
- Collection of verticies (nodes).  
- Possibly connected by line segments or edges.

## Terminology

**Vetetex** 
    - Node or data object that can have multpile adjacent vertecies.
**Edge**
    - Connection between two nodes.S
**Neighbor**
    - Adjacent nodes vonnection by edge.
**Degree**
    - Number of edges connected to vertex.  

## Undirectred Graph

- EDges do not move in a partiular direction.  
[Graph undirected](./img/undirectedGraph.png)  

## Directed Graph

- All edges are directed to a specific node or set of nodes.  

[Directed Graph](./img/DirGraph.png)  

## Complete Graph

- ALl nodes connect to eachother.  
[Complete Graph](./img/CompleteGraph.png)  

## Connected Graph

- All Verticies havae at least one edge.  
[Connected Graph](./img/ConnectedGraph.png)


## Disconnected Graph

- Some nodes do not connect to other nodes.  
[DisconnectSed Graph](./img/DisconnectedGraph.png)  


## Acyclic and Cyclic Graphs  

**Cycle**
    - When a node can traversed and end up at its self.  
    - Path of positive length.  

**Acyclic**
    - A Directed graph that does not contain cycles aslo known as tree or DAG.  
[Acyclic Graph](./img/AcyclicGraph.png)  

**Cyclic**
    - Graph with cycles.
[Cyclic Graph](./img/cyclicGraph.png)  

## Representation

- Can be represented in a matix or a list.  

## Traversals

**Breadth First**
    - Start at specific node.  
    - Similar to tree.  
    - Possible cycles  
    - Visited or unvistied property.  

**Depth First**
    - Push root into stack.  
    - Pop off top.  
    - Check for neighbors.  
    - If not vistied push to stack.  
    - Repeat.  

## Use Cases

- Gps/Mapping
- Directions
- Airline traffic
- Suggested profducts Netfilx  
