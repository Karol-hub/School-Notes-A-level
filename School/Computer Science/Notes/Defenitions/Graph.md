Set of vertices/nodes which are connected by edges

There are two types: 
- Directed 
	- Edges can only be traversed in one direction 
	- Edges point in a direction 

- Undirected 
	- Edges can be traversed in both directions 
	- Edges don’t point in a direction

Stored with:
![[Storing a graph.png]]

Adjacency Matrix Adv |Adjacency List Adv
---|---
Convenient to work with due to the quicker access times| More space efficient for large networks
Easy to add nodes|

Pseudocode representation
Edge {[“B”,”A”], [“B”,”C”], [“B”, E”], [“A”,”C”], [“A”,”D”], [“E”, D”], [“D”,”C”]}