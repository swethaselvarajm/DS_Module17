# Ex22 Breadth First Graph
## DATE:
## AIM:
To write a printQueue C function of the given graph that is to be traversed in the breadth first manner.

![image](https://github.com/user-attachments/assets/f483f48c-6af0-4027-a993-01c108a50933)


## Algorithm
1. Check if the queue is empty.
2. If empty, print a message indicating the queue is empty.
3. If not empty, start from the front of the queue.
4. Loop through all elements up to the rear and print them. 
5. End the function after printing all elements.  

## Program:
```
/*
Program to traverse graph using BFS
Developed by: SWETHA S
RegisterNumber: 212222230155 
*/
```
```
/*
void printQueue(struct queue* q) {
 //type your code here   
 int i = q->front;
 
 if(isEmpty(q))
 {
     printf("Queue is empty");
 }
 else
 {
     printf("Queue contains ");
     for(i=q->front;i<q->rear+1;i++)
     {
         printf("%d ",q->items[i]);
     }
 }
}
*/
```
## Output:

<img width="891" height="501" alt="image" src="https://github.com/user-attachments/assets/9b31abc6-9494-4742-9838-f43a51a6e713" />


## Result:
Thus, the code for the printQueue function of the following graph that is to be traversed in the breadth first manner is implemented successfully.
