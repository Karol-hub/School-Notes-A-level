1. a) Dijkstra's shortest path algorithm aims to find the shortest path between 2 nodes in a graph
   b) If there was a node representation of a map you could find the shortest route to travel, or if the map was a train system you could find the least amount of trains that you would have to go on to reach your destination
   c)
```mermaid 
flowchart LR
A("A")
B("B")
C("C")
D("D")
E("E")
F("F")
G("G")

A -- 8 --> E
B -- 5 --> E
A -- 4 --> D
A -- 4 --> B
B -- 9 --> C
D -- 9 --> E
D -- 7 --> F
D -- 10 --> C
E -- inf --- C
C -- inf --- G & F
F -- inf --- G
```
```mermaid 
flowchart LR
A("A")
B("B")
C("C")
D("D")
E("E")
F("F")
G("G")

A -- 8 --> E
B -- 5 --> E
A -- 4 --> D
A -- 4 --> B
B -- 9 --> C
D -- 9 --> E
D -- 7 --> F
D -- 10 --> C
E -- inf --- C
C -- 16 --- G
C -- 10 --- F
F --inf --- G
```
```mermaid 
flowchart LR
A("A")
B("B")
C("C")
D("D")
E("E")
F("F")
G("G")

A -- 8 --> E
B -- 5 --> E
A -- 4 --> D
A -- 4 --> B
B -- 9 --> C
D -- 9 --> E
D -- 7 --> F
D -- 10 --> C
E -- 8 --- C
C -- 15 --- G
C -- 10 --- F
F --11 --- G
```

	 d) i) A -> B -> E -> C 
	            length:8
		ii) A -> D -> F -> G
			    length:11

2. 

| Q   | Liverpool | Leeds | Manchester | Sheffield | York |
| --- | --------- | ----- | ---------- | --------- | ---- |
|   a | 0         | 75    | inf        | inf       | inf  |
|    b| 0         | 75    | 34         | inf       | inf  |
