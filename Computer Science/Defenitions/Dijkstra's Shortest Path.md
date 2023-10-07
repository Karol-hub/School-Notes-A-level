Finds the shortest path between two nodes in a weighted graph

method:
- Create a set **sptSet** (shortest path tree set) that keeps track of vertices included in the shortest path tree, i.e., whose minimum distance from the source is calculated and finalized. Initially, this set is empty. 
- Assign a distance value to all vertices in the input graph. Initialize all distance values as **INFINITE**. Assign the distance value as 0 for the source vertex so that it is picked first. 
- While **sptSet** doesn’t include all vertices 
    - Pick a vertex **u** that is not there in **sptSet** and has a minimum distance value. 
    - Include u to **sptSet**. 
    - Then update the distance value of all adjacent vertices of u. 
        - To update the distance values, iterate through all adjacent vertices. 
        - For every adjacent vertex v, if the sum of the distance value of u (from source) and weight of edge u-v, is less than the distance value of v, then update the distance value of v.

https://www.geeksforgeeks.org/dijkstras-shortest-path-algorithm-greedy-algo-7/