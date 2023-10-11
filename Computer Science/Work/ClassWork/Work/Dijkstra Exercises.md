![[Algorithms_Dijkstra_Exercises.pdf]]
1. 

| Node | Shortest Distance to A | Previous Node | Visited? |
| ---- | ---------------------- | ------------- | -------- |
| A    | 0                      | N/A           | Y        |
| B    | 4                      | A             | Y        |
| C    | 7                      | A             | Y        |
| D    | 12                     | C             | Y        |
| E    | 10                     | E             | Y        |
| F    | 9                      | B             | Y        |
| G    | 19                     | B             | Y        |
| H    | 13                     | D             | Y        |
| I    | 15                     | E             | Y        |
| J    | 27                     | G             | Y        |

A -> B - > G -> J
Dist: 27
Correct
2. 

| Node | Shortest Distance to H | Previous Node | Visited? |
| ---- | ---------------------- | ------------- | -------- |
| A    | 23                     | C             | Y        |
| B    | 26                     | E             | Y        |
| C    | 16                     | D             | Y        |
| D    | 11                     | H             | Y        |
| E    | 20                     | C             | Y        |
| F    | 33/31                  | B             | Y        |
| G    | 26                     | J             | Y        |
| H    | 0                      | N/A           | Y        |
| I    | 31/25                  | E             | Y        |
| J    | 18                     | H             | Y        |

H->D->C->E->B
Dist: 26
Correct
3. 

| Node | Shortest Dist to D | Prev Node | Used |
| ---- | ------------------ | --------- | ---- |
| A    | 12                 | C         | Y    |
| B    | 15                 | E         | Y    |
| C    | 5                  | D         | Y    |
| D    | 0                  | N/A       | Y    |
| E    | 9                  | C         | Y    |
| F    | -22-/20            | -I-/B     | Y    |
| G    | 30                 | B         | Y    |
| H    | 11                 | D         | Y    |
| I    | 14                 | E         | Y    |
| J    | -29-/27            | -H-/I     | Y    |

D->C->E->B->G
Dist: 30
Correct