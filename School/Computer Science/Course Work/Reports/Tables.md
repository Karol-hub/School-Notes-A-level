
| Test Number | Input | Expected Result                                             | Actual Result                       | Improvements for future                                                               |
| ----------- | ----- | ----------------------------------------------------------- | ----------------------------------- | ------------------------------------------------------------------------------------- |
| 1           | None  | Rooms generated in a dense section around coordinates (0,0) | ![[Failed to build.png]]            | Tried to access Node's position which doesn't exist, need to access Area2D's position |
| 2           | None  | Rooms generated in a dense section around coordinates (0,0) | ![[Nothing happened.png]]           | Forgot to assign a parent to the rooms so they didn't generate at all.                |
| 3           | None  | Rooms generated in a dense section around coordinates (0,0) | ![[rooms generated successful.png]] | Will be improved upon in the next iteration, but functions currently                  |
