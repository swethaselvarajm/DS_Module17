# Ex23 Depth First Graph
## DATE:
## AIM:
To compose the code for the function createNode to traverse the graph below in the depth first fashion.

![image](https://github.com/user-attachments/assets/63552824-d0a3-49c6-a473-6db27d1f03e4)

## Algorithm
1. Allocate memory for a new node.
2. Assign the vertex value to the new node.
3. Initialize the next pointer of the node to NULL.
4. Return the newly created node. 
5. Use this node in DFS traversal to build adjacency lists.  

## Program:
```
/*
Program to traverse the graph below in the depth first fashion
Developed by: SWETHA S
RegisterNumber: 212222230155 
*/
```
```
/*
struct node* createNode(int v) {
  struct node* newNode = malloc(sizeof(struct node));
  newNode->vertex = v;
  newNode->next = NULL;
  return newNode;
}
*/
```
## Output:
<img width="536" height="810" alt="image" src="https://github.com/user-attachments/assets/406156dc-c7db-43ab-af7b-949962bb92a2" />



## Result:
Thus, the C code for the function createNode to traverse the graph below in the depth first fashion is implemented successfully
