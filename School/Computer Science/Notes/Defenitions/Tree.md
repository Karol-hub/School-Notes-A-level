# Explanation
Form of graph where the top node is the root of the tree, and lower down nodes are connected using branches and are children of the higher-level nodes

![[Tree def.png]]

Binary tree is where each node can have a maximum of two children and can be represented in a 2d array as seen below, these trees are easy to search through

![[Binary tree.png]]
# Code
## Adding an item
1. Check if there is room in memory for a new nodes, if there isn't output an error
2. Create a new node and insert data onto it
3. If the binary tree is empty
	1. The new node becomes root node, create starter pointer to it
4. IF the binary tree isn't empty
	1. Start at the root node
	2. if the new node should be placed before the current node follow the left pointer
	3. If the new node should be placed after the current node follow the right pointer
	4. Repeat step 4.2/4.3 until a leaf node is reached
	5. If the new node should be placed before the current node set the left pointer to be the new node
	6. If the new node should be placed after the current node set the right pointer to be the new node
## Removing an item
1. Start at the root  node and set it as the current node
2. while the current mode exists and it is not the one to be deleted
	1. Set the previous node variable to be set the same as the current node
	2. If the item to be deleted is less than the current node follow the left pointer and set the discovered node as the current node
	3. If the item to be deleted is greater than the current node, follow the right pointer and set the discovered node as the current node.
3 Cases:
- Node is a Leaf node (has no children)
	1. If the previous node is greater than the current node, the previous node's left pointer is set to null.
	2. If the previous node is less than the current node, the previous node's right pointer is set to null.
- Node has one child
	1. If the current node is less than the previous node:
		1. Set the previous node's left pointer to the current node's left child.
	2. If the current node is greater than the previous node:
		1. Set the previous node's right pointer to the current node's right child.
- Node has 2 children
	1. If a right node exists and it has a left sub-tree, find the smallest leaf node in the right sub-tree:
		1. Change the current node to the smallest leaf node.
		2. Remove the smallest leaf node.
	2. If a right node exists and it has no left sub-tree:
		1. Set the current node to be the current node's right pointer.
		2. Set the current node's right pointer to null.
## Traversal
###  [[Pre-order traversal]]
1. Start at root node
2. Output the node
3. Follow the left pointer and repeat from step 2 until there is no pointer to follow
4. Follow the right pointer and repeat from step 2 until there is no pointer to follow
### [[In-order traversal]]
1. Start at root node
2. Follow left pointer and repeat from step 2 until there is no pointer to follow
3. Output the node
4. Follow the right pointer and repeat from step 2 until there is no pointer to follow
### [[Post-order traversal]]
1. Start at the root node.
2. Follow the left pointer and repeat from step 2 recursively until there is no pointer to follow.
3. Follow the right pointer and repeat from step 2 recursively until there is no pointer to follow
4. Output the node.