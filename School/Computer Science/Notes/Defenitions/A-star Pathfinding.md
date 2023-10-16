- Improvement of [[Dijkstra's Shortest Path]] algorithm
- Has 2 cost functions
	- Actual cost function just like in [[Dijkstra's Shortest Path|Dijkstra's]]
	- Heuristic
		- Is a measure of how far away path is from target node using trig
		- Aims to make algorithm more efficient

1. Set initial g and f values for all nodes in the graph.
2. Until the goal node has been visited:
	1. Find the node with the lowest f value that has not been visited.
	2. For each connected node that has not been visited:
		1. Calculate the relative distance from the start by adding the edge value and the heuristic.
		2. If the distance from the start plus the heuristic is lower than the currently recorded f value:
			1. Set the f value of the connected node to the newly calculated distance.
			2. Set the previous node to be the current node.
	3. Set the current node as visited.
