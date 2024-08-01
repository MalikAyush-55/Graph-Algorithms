Overview
This project implements Dijkstra's Algorithm to find the shortest path from a source vertex to all other vertices in a graph using a min-priority queue, with a time complexity of O(V + ElogV).

Files
main.cpp: Contains the implementation of Dijkstra's Algorithm.
Functions
createAndAddEdge
Purpose: Adds a directed edge with a specified weight from vertex u to vertex v in the adjacency list.
Usage: Used to build the graph by adding edges.
DijkstrasAlgorithm
Purpose: Executes Dijkstra's Algorithm to compute the shortest paths from the source vertex to all other vertices.
Usage: Called to find and display the shortest paths from the source vertex.
main
Purpose: The driver function that sets up the graph, calls Dijkstra's Algorithm, and prints the results.
Usage: Entry point of the program.