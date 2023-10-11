First in first out (FIFO) 
Enqueue
- add item to queue
Dequeue
- item is removed from queue

In a linear queue there are two pointers, one in the front of the list and one in the end
![[queue example.png]]

Leaves blank spaces in memory when items are removed

There are circular queues which attempt to solve this problem by looping around when the queue is full
![[Circular queue.png]]
it is harder to implement but it is more space efficient in memory

queue overflow
- item added to full queue
queue underflow
- item removed from empty queue

Priority queue allows items to jump the queue