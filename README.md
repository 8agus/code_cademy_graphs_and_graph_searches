# code_cademy_graphs_and_graph_searches

## Introduction to Graphs

We’ll build a robust implementation of the graph data structure. With just two classes, Vertex and Graph, we can implement a variety of graphs that satisfy the requirements of many algorithms.

Let’s detail the functionality we require from these classes:

* Vertex stores some data.
* Vertex stores the edges to connected vertices and their weight.
* Vertex can add a new edge to its collection.
* Graph stores all the vertices.
* Graph knows if it is directed or undirected.
* Graph can add a new vertex to its collection.
* Graph can add a new edge between stored vertices.
* Graph can tell whether a path exists between stored vertices.

Since we’re dealing with multiple classes, we’ll use multiple files for this implementation. To keep the concepts grounded in a real-world application, we’ll build up a transportation network of railroads and train stations as we go.


## Implementing a Graph Class

The basis of a Graph class in Python is the implementation of two classes, Graph and Vertex, which establish the essential functionality to create a variety of graphs.

The Vertex class allows for storage of connecting vertices with a dictionary and adjustment of their edges as well.

The Graph class builds upon the Vertex methods and allows addition of vertices and edges, setting the directionality of edges, and determining if a path exists between two vertices.

<img width="392" alt="image" src="https://user-images.githubusercontent.com/82447615/188574368-6e9dfba1-249e-4623-8848-77608139cfc1.png">
