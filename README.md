# Proiect-Licenta
Drumuri in graf folosind OpenMP

# Abstract
The area of algorithm analysis and assessment is the focus of this study. This
research offers a substantial addition to computer science by investigating and developing testing as well as algorithmic analysis employing effective methods on
graphs, such as finding the shortest path between any two nodes or breadth-first
traversal in a graph. The goal of this project is to provide a tool that allows users
to apply algorithms like Dijkstra, Bellman Ford, and BFS (Breadth First Search) on
graphs. The project consists of 8 chapters, 5 of which cover the theoretical part and
3 for the practical part.
The project’s idea, goal, and context are described in the theoretical section, along
with the theories needed to understand the graphs, the purpose of the algorithms
that must be executed within the application, the advantages of using the OpenMP
library for parallelizing algorithms and an analysis of the metrics used to implement
algorithms over various-sized graphs. A unique contribution is the creation of a
set of data that highlights the need for parallelizing algorithms in comparison to
sequential execution. The collected data demonstrates that as the size of the graph
grows, parallel execution becomes more efficient.
The description of the application from the implementation perspective, examples of real-world situations where it can be used effectively, a clear separation of
the architecture into client and server, implementations of these components, and
the use of the user interface by picturing the website are all covered in the practical
section. My own contribution to this section includes the scratch implementation of
the sequential and parallel Dijkstra, Bellman Ford, and BFS algorithms, as well as
my own design that was influenced by existing resources.
Due to the parallel execution type’s superior efficiency versus sequential execution, the application was created to demonstrate the advantages of parallelizing
algorithms. Dijkstra, Bellman Ford, and BFS were among the algorithms utilized,
and the application was developed utilizing frameworks and libraries including
OpenMP for parallel distribution using threads, Spring for connecting server and
client sides, and Cytoscape for graph visualization.
