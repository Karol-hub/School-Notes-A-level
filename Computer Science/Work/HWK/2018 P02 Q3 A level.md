![[Pasted image 20231013124519.png]]
A tree has a root node whereas a graph doesn't
![[Pasted image 20231013124632.png]]
Doesn't show any walls or room layouts, only shows connections and removes all detail apart from that.
![[Pasted image 20231013124740.png]]
1. Don't need to process any more data
2. Shows the layout of the puzzle
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

![[Pasted image 20231013125742.png]]

Dijkstra's algorithm has to go through every possible scenario 