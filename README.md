# metro-route-finder
Problem Statement: 
There are millions of people who find it difficult to find the right route for their destination in the Delhi Metro. They face a lot of queries like which is the shortest route or the economical path for their journey. So here we are with the solution to this problem with a program named Metro Route Finder. 
 
Introduction: 
Metro Route Finder is a program written in C++ language, which can be beneficial for the people in their day-to-day metro life. It helps in finding out the shortest and the most economical path between two travel destinations on Delhi Metro. This program is also useful for the tourists as it helps to find the nearest metro station to popular tourist destinations like Lotus Temple, India gate, etc. One more feature added in this program is the recharge of the metro card. 
  
 
List of Data Structures used in the project: 
The language used for the completion and implementation of the aimed topic is C++. 
Data structures used in the program are – 
 
Maps- A Map is a type of fast key lookup data structure that offers a flexible means of indexing into its individual elements These keys, along with the data values associated with them, are stored within the Map. Each entry of a Map contains exactly one unique key and its corresponding value. Here in this project, it is used for mapping stations and distances. 
 
Vector- Vectors are same as dynamic arrays with the ability to resize itself automatically when an element is inserted or deleted, with their storage being handled automatically by the container. Vector elements are placed in contiguous storage so that they can be accessed and traversed using iterators. In vectors, data is inserted at the end. 
 
String- Strings are defined as an array of characters. The difference between a character array and a string is the string is terminated with a special character ‘\0’. It is used to input the names of the stations. 
 
Graph- A Graph is a non-linear data structure consisting of nodes and edges. The nodes are sometimes also referred to as vertices and the edges are lines or arcs that connect any two nodes in the graph.  Graphs are used to represent networks that is the path between two stations. Graphs involves the usage of the adjacency matrix which is use to link the stations with each other. 
 
Pair- The pair container is a simple container defined in <utility> header consisting of two data elements or objects. The first element is referenced as 'first' and the second element as 'second' and the order is fixed (first, second). Pair is used to combine together two values which may be different in type. Stack- Stack is a linear data structure which follows a particular order in which the operations are performed. It follows the order LIFO(Last in First Out). It is used here for storing the input stations in the order they appear from source to the destination. 
 
Priority queue- It is an abstract data type similar to a regular queue or stack data structure in which each element additionally has a "priority" associated with it. In a priority queue, an element with high priority is served before an element with low priority. It is used here to arrange the stations in the priority of distances.  
 
Breadth first search- It is an algorithm that is used to graph data or searching tree or traversing structures. It starts at the tree root and explores all of the neighbour nodes at the present depth prior to moving on to the nodes at the next depth level. So, it is used to find the shortest path between two stations.  
 
Dijkstra’s algorithm- Used to find shortest paths from source to all vertices in the given graph. Dijkstra’s algorithm is very similar to Prim’s algorithm for minimum spanning tree. Here it is used to calculate the most economical path between the source and destination station. 
 
 ![image](https://user-images.githubusercontent.com/71588326/180058224-1d51e3c5-7a85-468e-8b7f-ede82e92f955.png)

 
 
 
 
  
  
  
 
 
 
 
 
 
 
 
 
  
 
  
 
  
 
  
 
  
  
 
 
 
 
 
 
 
 
 
Implementation details and results: 
This program is built by combining mainly two important data structures – Breadth first search and Dijkstra’s algorithm. 
We say that BFS is the algorithm to use if we want to find the shortest path in an undirected, unweighted graph. The claim for BFS is that the first time a node is discovered during the traversal, that distance from the source would give us the shortest path.  
 ![image](https://user-images.githubusercontent.com/71588326/180058363-9f186889-d2d8-4407-993f-e107771b57c0.png)

  
The Time complexity of BFS is O(V + E) when Adjacency List is used and O(V^2) when Adjacency Matrix is used, where V stands for vertices and E stands for edges. 
Dijkstra’s algorithm can be used to determine the shortest path from one node in a graph to every other node within the same graph data structure, provided that the nodes are reachable from the starting node. 
 
  
Time Complexity of Dijkstra's Algorithm is O ( V 2 ) but with minpriority queue it drops down to O ( V + E l o g V ) . 
 
•	To check the route between two stations which specifies all the metro stations needed to be covered with the additional information about the interchanging stations i.e., where the metro line will change. This gives the information about the most economic path. 
  
 ![image](https://user-images.githubusercontent.com/71588326/180058428-55c03b25-1bd4-4116-950a-2ca4af49ced0.png)

•	To check the route between two stations which would be the shortest path between the source and destination station. 
  ![image](https://user-images.githubusercontent.com/71588326/180058453-8d58fd0a-f6d0-4fa3-8b41-40e87702c623.png)

•	To check the nearest metro station to a tourist place we input the tourist spot and on entering it we get know the station name closest to it. 
•	Also helps to recharge the smart metro card instantly. 
 ![image](https://user-images.githubusercontent.com/71588326/180058481-281c0bca-6baf-4c92-a12b-121712631a77.png)

  
 
 
 
 
 
 
 
 

