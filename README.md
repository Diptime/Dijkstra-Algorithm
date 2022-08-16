Dijkstra algorithm is also called single source shortest path algorithm. It is based on greedy technique.
The algorithm maintains a list visited[ ] of vertices, whose shortest distance from the source is already
known.If visited[1], equals 1, then the shortest distance of vertex i is already known. Initially, 
visited[i] is marked as, for source vertex. At each step, we mark visited[v] as 1. Vertex v is a vertex 
at shortest distance from the source vertex. At each step of the algorithm, shortest distance of each 
vertex is stored in an array distance[ ].

This repository includes the source code for a Dijkstra Algorithms Visualiser. We can calculate the 
shortest path between the two nodes and shoe the graphical view using the code. It has been 
developed using C++ .

Visualizer in action:
The visualizer uses the following 5 colors :
->	Blue for  the starting node
->	Purple for ending node
->	Yellow for relaxed nodes
->	Brown for path node 
->	White for obstacle nodes
(By nodes, small squares in the grid are refered).

At the start of the algorithm,we are asked to first select the starting and the ending nodes in the grid.
Once this is done we are asked if we want to add obstacles in the path of the grid and input is received 
in as Y/N(yes or no).Upon completion of these steps we are shown (one of the ) shortest paths between the
starting and ending nodes. The visual keys for colour code are also present in the output screen to avoid
any confusion.

Snapshots from the project is included below:

Output screen :

![image](https://user-images.githubusercontent.com/73034611/184841837-d93b5be4-3f14-4d92-b808-94acde2d4d9f.png)

Shortest path and it's distance :

![image](https://user-images.githubusercontent.com/73034611/184841955-a839e8fe-6efd-4db9-b7c2-3120b169caac.png)

