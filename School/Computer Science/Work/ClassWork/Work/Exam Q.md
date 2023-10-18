![[Pasted image 20231018102124.png]]
[2/2]
![[Pasted image 20231018102032.png]]
[3/3]
![[Pasted image 20231018101626.png]]
First checks if the value is empty and then iterates through list until "Hosta" is found and checks the item before Hosta (in this case daisy) and updates the next pointer to the next pointer of Hosta (7), it also needs to make sure to release the memory that the "Hosta" item took so that it's not wasted.
[4/4]
![[Pasted image 20231018102511.png]]
```
# Python Notation
plantList = [["Begonia",1],
             ["Daisy",2],
             ["Hosta",7],
             ["Lily",4],
             ["Peony",5],
             ["Rose",6],
             ["Sunflower",None],
             ["Lavender",3]]

pointer = 0
while pointer != None:
    print(plantList[pointer][0])
    pointer = plantList[pointer][1]
```
[4/5]
it says add comments so add comments (read Q)