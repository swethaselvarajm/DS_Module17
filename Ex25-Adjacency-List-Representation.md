# Ex25 Adjacency List Representation
## DATE:
## AIM:
To write a C program to represent the given graph using the adjacency list.

## Algorithm
1. Define a struct node to represent each adjacency list node.
2. Define a struct Graph containing the number of vertices and an array of adjacency lists.
3. For each vertex, traverse its linked list to print all connected vertices.
4. Use while loop to go through each node in the adjacency list. 
5. Print the adjacency list of all vertices sequentially.  

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: SWETHA S
RegisterNumber: 212222230155 
*/
```
```
/*
void printGraph(struct Graph* graph)
{
  int v;
  for (v = 0; v < graph->numVertices; v++)
  {
    struct node* temp = graph->adjLists[v];
    printf("Vertex %d: -> ", v);
    while (temp->next!=NULL)
    {
      printf("%d -> ", temp->vertex);
      temp = temp->next;
    }
    printf("%d", temp->vertex);
    printf("\n");
  }
}
*/
```
## Output:

<img width="672" height="494" alt="image" src="https://github.com/user-attachments/assets/16a0c2aa-8272-48dd-a910-a80c1a1c8fee" />


## Result:
Thus, the C program to represent the given graph using the adjacency list is implemented successfully
