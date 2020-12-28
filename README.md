# generic-graph
This is a Java implementation of a graph, which uses a generic class in order to provide flexibility and effective code reuse for a myriad of use cases.

In graph theory, a graph is a mathematical structure comprised of *nodes* connected by *edges*. Data is contained within these nodes which act as an abstraction of representing connections between objects and within structures.
My graph implementation uses a **hash map**, where an object (the node) maps to a **linked list** containing the neighbours of the node in question.

The methods include mutators that add vertices and edges to the graph, as well as algorithms such as Breadth-First Search (BFS) and Depth-First Search (DFS).
This allows for a rapid development of directed and undirected unweighted graphs with the most commonly used algorithms in practice.  
