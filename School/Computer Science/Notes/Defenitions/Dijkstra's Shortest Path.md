Finds the shortest path between two nodes in a weighted graph

method:
1. Set the initial distance from the start values for all nodes
2. For each node in the graph:
	1. Find the nodes with the shortest distance from the start that hasn't been visited
	2. For each connected node that hasn't been visited 
		1. Calculate the distance from the start
		2. If the distance from the start is lower than the current recorded distance from the start
			1. Set the shortest distance to the start of the connected nods to the newly calculated distance
			2. set the previous node to be the current node
3. Mark the node as visited

https://www.geeksforgeeks.org/dijkstras-shortest-path-algorithm-greedy-algo-7/