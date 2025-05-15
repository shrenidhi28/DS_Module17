# Ex23 Depth First Graph
## DATE: 24-04-25
## AIM:
To compose the code for the function createNode to traverse the graph below in the depth first fashion.

![image](https://github.com/user-attachments/assets/63552824-d0a3-49c6-a473-6db27d1f03e4)

## Algorithm
1. Start
2. Allocate memory for a new node.
3. Set the vertex field of the new node to the given value v.
4. Set the next pointer of the new node to NULL.
5. Return

   
## Program:
```
/*
Program to traverse the graph below in the depth first fashion
Developed by: C>Shrenidhi
RegisterNumber:  212223040196
*/

/*#include <stdio.h>
#include <stdlib.h>
struct node {
int vertex;
struct node* next;
};
struct node* createNode(int v);
struct Graph {
int numVertices;
int* visited;
// We need int** to store a two dimensional array.
// Similary, we need struct node** to store an array of Linked lists
struct node** adjLists;
};*/
struct node* createNode(int v) {
struct node* newNode=malloc(sizeof(struct node));
newNode->vertex=v;
newNode->next=NULL;
return newNode;
}

```

## Output:
<img width="352" alt="image" src="https://github.com/user-attachments/assets/3657aef6-0d7d-40e1-9e59-eb7aeefb4b1f" />




## Result:
Thus, the C code for the function createNode to traverse the graph below in the depth first fashion is implemented successfully
