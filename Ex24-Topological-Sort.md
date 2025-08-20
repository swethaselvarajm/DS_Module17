# Ex24 Topological Sort
## DATE:
## AIM:
To compose the code to determine whether the topological ordering for the following graph is possible or not.

![image](https://github.com/user-attachments/assets/c74a7111-9b59-475c-aad4-9baf23d50ec0)


## Algorithm
1. Create a graph and initialize adjacency matrix.
2. Calculate the in-degree of each vertex.
3. Enqueue all vertices with in-degree 0.
4. While the queue is not empty, remove a vertex, append it to the topological order, and reduce the in-degree of its neighbors. 
5. If all vertices are processed, print the topological order; otherwise, report that the graph contains a cycle.  

## Program:
```
/*
Program to determine whether the topological ordering for the following graph is possible or not
Developed by: SWETHA S
RegisterNumber: 212222230155 
*/
```
```
/*
int main()
{
        int i,v,count,topo_order[MAX],indeg[MAX];

        create_graph();

        /*Find the indegree of each vertex*/
        for(i=0;i<n;i++)
        {
                indeg[i] = indegree(i);
                if( indeg[i] == 0 )
                        insert_queue(i);
        }

        count = 0;

        while(  !isEmpty_queue( ) && count < n )
        {
                v = delete_queue();
        topo_order[++count] = v; /*Add vertex v to topo_order array*/
                /*Delete all edges going from vertex v */
                for(i=0; i<n; i++)
                {
                        if(adj[v][i] == 1)
                        {
                                adj[v][i] = 0;
                                indeg[i] = indeg[i]-1;
                                if(indeg[i] == 0)
                                        insert_queue(i);
                        }
                }
        }

        if( count < n )
        {
                printf("No topological ordering possible, graph contains cycle\n");
                exit(1);
        }
        printf("Vertices in topological order are :\n");
        for(i=1; i<=count; i++)
                printf( "%d ",topo_order[i] );
        printf("\n");

        return 0;
}/*End of main()*/
*/
```
## Output:

<img width="1110" height="488" alt="image" src="https://github.com/user-attachments/assets/8a95e75d-8568-404b-9a5e-3a959696a545" />


## Result:
Thus, the C program for determining whether the topological ordering for the following graph is possible or not, is implemented successfully.
