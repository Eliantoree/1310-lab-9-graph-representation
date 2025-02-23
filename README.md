# 1310-lab-9-graph-representation
1310 – lab 9 graph representation

**Download Link:https://programming.engineering/product/1310-lab-9-graph-representation/**

Description
5/5 – (2 votes)
files that should be included in your submission
GraphList.h
Driver.cpp
graph.txt
Given Files
graph.txt
lab specifications (directions on how to write the program)
main.cpp
Open graph.txt
Read the number of vertices
Create your adjacency list object based on the number of vertices
Use a loop to read from the file the edges and add the edge to the adjacency list
Make sure to print what edge is being added (refer to sample output)
Print the adjacency list (refer to sample output)
GraphList.h
Private attributes:
ListNode structure (containing integer value & pointer to next ListNode
ListNode ** headArray; (array of linked lists)
int numVertices
int numEdges
Public Member Functions:
constructor – accepts an integer (the number of vertices in the graph), sets the private attribute numVertices, dynamically allocates an array of pointers to ListNodes
destructor – deletes linked lists
addEdge – accepts two vertices – create the node & add it to appropriate linked list
printGraph – prints the matrix
Sample Output
There are 7 vertices in the graph.

Adding an edge from 0 to 1.

Adding an edge from 0 to 2.

Adding an edge from 1 to 4.

Adding an edge from 1 to 6.

Adding an edge from 2 to 5.

Adding an edge from 3 to 0.

Adding an edge from 3 to 1.

Adding an edge from 3 to 2.

Adding an edge from 3 to 5.

Adding an edge from 3 to 6.

Adding an edge from 6 to 4.

Adding an edge from 6 to 5.

Adjacency List…

0—>1—>2—>NULL

1—>4—>6—>NULL

2—>5—>NULL

3—>0—>1—>2—>5—>6—>NULL

4—>NULL

5—>NULL

6—>4—>5—>NULL
