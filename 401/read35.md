# Read35 Summary

![graphs](https://www.geeksforgeeks.org/wp-content/uploads/undirectedgraph.png)

A Graph is a non-linear data structure consisting of nodes and edges. The nodes are sometimes also referred to as vertices and the edges are lines or arcs that connect any two nodes in the graph. Graphs are used to solve many real-life problems. Graphs are used to represent networks. The networks may include paths in a city or telephone network or circuit network. Graphs are also used in social networks like linkedIn, Facebook. For example, in Facebook, each person is represented with a vertex(or node). Each node is a structure and contains information like person id, name, gender, locale etc.

* Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
* Edge - An edge is a connection between two nodes.
* Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
* Degree - The degree of a vertex is the number of edges connected to that vertex.

![directed vs undirected](https://364c96dc-a-21b3d60d-s-sites.googlegroups.com/a/cs.christuniversity.in/discrete-mathematics-lectures/graphs/directed-and-undirected-graph/dir.png?attachauth=ANoY7cq1pJpcMfFwVs_wEBwyFP5vOo4Ds0fzFgIzpYB9Ma1pi9R9vi5Uz-QUwqaPbZF1zDaoiQvTgBGgX-aw5gveThWDmR1-wICmoQ8rUTmNhs3RkzPlWRVUElCJywcd0kzHQGT0pUuVh-hcM5w1A9_dHEZYM9tbfXpkBzrg1gpE54P84qx2_HLKSHfCQGaz1nKvWDAtubnPNn8Py4GbJjz44uZxZzbFJASXjjMkfh5CHLJvWrlsm71wxa9ad6Fk32u7XrnSPTy1fQoA3b-hvPcnj61CIFzhcabaLvPqf8tBF7sLo2bJNCo%3D&attredirects=0)

| Directed graph  | Undirected graph  |
|---|---|
|  A directed graph is a set of vertices (nodes) connected by edges, with each node having a direction associated with it |   An Undirected Graph is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.|
| Edges are usually represented by arrows pointing in the direction the graph can be traversed. |  The edges are bidirectional, with no direction associated with them. Hence, the graph can be traversed in either direction. The absence of an arrow tells us that the graph is undirected.  |
| In directed graphs, arrows represent the edges| in undirected graphs, undirected arcs represent the edges.  |

![connected vs disconnected](https://i0.wp.com/algorithms.tutorialhorizon.com/files/2019/10/Connected-Undirected-Graph-Example.png?resize=967%2C397&ssl=1)

* Connected graph - A graph is connected if all nodes have at least one edge.
* Disconnected graph - A graph where some vertices may not have edges.

![complete graph](https://www.researchgate.net/profile/Oemuer-Kuerkcue/publication/330170487/figure/fig7/AS:713525953560590@1547129252859/A-complete-graph-a-K10-and-its-adjacency-matrix-plot-b.png)

A complete graph is a simple undirected graph in which every pair of distinct vertices is connected by a unique edge. A complete digraph is a directed graph in which every pair of distinct vertices is connected by a pair of unique edges (one in each direction). A complete graph is when all nodes are connected to all other nodes.

![cyclic vs acyclic](https://i.imgur.com/2z9J2E5.png)

* A cyclic graph means that there contains a least one cycle within the graph.
* An acyclic graph has no cycles within it.

![adjacency matrix](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/AdjMatrix.PNG)

An adjacency matrix is a square matrix used to represent a finite graph. The elements of the matrix indicate whether pairs of vertices are adjacent or not in the graph.It is represented through a 2-dimensional array. If there are n vertices, then we are looking at an n x n Boolean matrix Each Row and column represents each vertex of the data structure. The elements of both the column and the row must add up to 1 if there is an edge that connects the two, or zero if there isn’t a connection.

![adjacency list](https://kajabi-storefronts-production.kajabi-cdn.com/kajabi-storefronts-production/blogs/27029/images/FVKdPFTlTmyXQBiypTge_375dbebabc31445637557c91ec1fe4de.jpg)

An adjacency list is a collection of unordered lists used to represent a finite graph. Each unordered list within an adjacency list describes the set of neighbors of a particular vertex in the graph. This is one of several commonly used representations of graphs for use in computer programs.

![weighted graphs](http://www.mathcs.emory.edu/~cheung/Courses/171/Syllabus/11-Graph/FIGS/Dijkstra/weight01.gif)

A weighted graph is a graph in which each branch is given a numerical weight. A weighted graph is therefore a special type of labeled graph in which the labels are numbers (which are usually taken to be positive).

![traversal](https://media.geeksforgeeks.org/wp-content/cdn-uploads/Preorder-from-Inorder-and-Postorder-traversals.jpg)

Traversing a tree allows us to search for a node, print out the contents of a tree, and much more! There are two categories of traversals when it comes to trees:

* Depth First - It is where we prioritize going through the depth (height) of the tree first. There are multiple ways to carry out depth first traversal, and each method changes the order in which we search/print the root.

* Breadth First - It iterates through the tree by going through each level of the tree node-by-node