![[Pasted image 20231013124519.png]]
A tree has a root node whereas a graph doesn't [1]
![[Pasted image 20231013124632.png]]
Doesn't show any walls or room layouts, only shows connections and length and removes all detail apart from that. [2/2]
![[Pasted image 20231013124740.png]]
1. Don't need to process any more data
2. Shows the layout of the puzzle [2/2]
![[Pasted image 20231013124931.png]]

| Node | Distance | Last Node | Used |
| ---- | -------- | --------- | ---- |
| A    | 0        | N/A       | Y    |
| B    | 5        | A         | Y    |
| C    | 13       | B         | Y    |
| D    | 14       | B         | Y    |
| E    | 8        | B         | Y    |
| F    | 15       | I         | Y    |
| G    | 15       | C         | Y    |
| H    | 18       | G         | Y    |
| I    | 12       | E         | Y    |
| J    | 14       | I         | Y    |
A->B->E->I->J
length: 14 [5/6]
Make sure to show updated path

![[Pasted image 20231013125742.png]]

Dijkstra's algorithm has to go through every possible scenario to find the most efficient route which means it has to check every edge in the graph, this isn't efficient, A* [1] search is more efficient because it assigns every node a heuristics which is a value determining how close the node is to the target[1], this means that the first path is usually the most efficient path[1]. Heuristics aims to make the path finding more efficient as it's taking in the heuristics into account when determining the shortest path. This means that the algorithms doesn't check the paths which lead away from the target like Dijkstra's would which means that it's checking paths which won't give any meaningful results. Whereas A* won't check those nodes because their heuristics make their priority low[1]. A* does need to find the heuristic value for each node which can make it less efficient, this makes it less useful for scenarios where the heuristic of every node changes constantly, but if the heuristics don't change then they can be pre-calculated and the algorithm is a lot more efficient then Dijkstra's algorithm. 
[5/9]
difference between how paths work 
talk about size of the data set
big O notation

![[Pasted image 20231014153118.png]]
1. Code compiler [1]
	1. Allow the developer to quickly compile code and run it, this can be used for testing and exporting the product
2. Libraries [1]
	1. Allow developer to use common code functions that may be less efficient if they were developed by the programmer (e.g. Math libraries)
3. Source code editor [1]
	1. Allows the developer to actually write the source code.
[6/6]