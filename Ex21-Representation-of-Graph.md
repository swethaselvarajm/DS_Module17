# Ex21 Representation of Graph
## DATE:
## AIM:
To write a C program to display the adjacency matrix of the given graph by supplying the edges and the number of vertices.

## Algorithm
1. Read the number of vertices V.
2. Initialize a V x V adjacency matrix with all values set to 0.
3. Read pairs of vertices representing edges until a sentinel value (-1 -1) is entered.
4. For each edge (u, v), mark adjMatrix[u][v] = 1 (and adjMatrix[v][u] = 1 if undirected). 
5. Print the adjacency matrix.  

## Program:
```
/*
Program to display the adjacency matrix of the given graph
Developed by: SWETHA S
RegisterNumber: 212222230155 
*/
```
```
/*
int main()
{   
    int e1,e2,me,n,i;
    scanf("%d",&V);
    int adjMatrix[V][V];

    init(adjMatrix);
    n=V;
    me=n*(n-1);
    for(i=1;i<=me;i++)
    {  
    scanf("%d%d",&e1,&e2);
    addEdge(adjMatrix, e1,e2);
    if((e1==-1)&&(e2==-1))
       break;
    }
  printAdjMatrix(adjMatrix);
  return 0;
}
*/
```
## Output:

<img width="366" height="476" alt="image" src="https://github.com/user-attachments/assets/fdcf51bc-0f05-4048-b3e4-55beb04bc4fe" />


## Result:
Thus, the C program to print the adjacency matrix of the given graph is implemented successfully.
