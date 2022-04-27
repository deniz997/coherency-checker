# Coherency Checker using DFS

This algorithm gets a graph as an adjacency matrix input and checks if the given graph is coherent by using dept-first search algorithm (DFS).

**Inputs**
* Dimensions of the adjacency matrix
* Values of the adjacency matrix

In a regular DFS, when a node has multiple neighbors, next node can be any of these neighbors. However, for the
consistency between answers, here the node with the smallest number is selected.

**Sample Input**

5\
1 0 0 1 0\
0 0 0 0 1\
0 0 1 0 0\
1 1 1 1 0\
0 0 1 0 0

Input graph:

<img src="https://user-images.githubusercontent.com/36201330/165468833-2e6fd4c3-08e0-4865-a332-a62b4e251472.png" width=400>

5 means that the input matrix has a size of 5x5.
Then, the following 25 values are read.

**Sample Output**

nein
