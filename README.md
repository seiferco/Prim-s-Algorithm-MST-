# Prim's Algorithm (Minimim Spanning Tree)
This project implements Prim's Algorithm to find the Minimum Spanning Tree (MST) of a given graph. Prim's Algorithm is a greedy algorithm that finds a subset of the edges that connects all vertices in the graph with the minimum total edge weight and without any cycles.

## Problem Description
Given an undirected graph represented as an adjacency matrix, the goal is to find the Minimum Spanning Tree. The graph is represented by a 2D list where each element G[i][j] represents the weight of the edge between vertex i and vertex j. If there is no edge, the weight is represented as 0.

#### Example
For the input graph:
graph1 = [
    [0, 8, 5, 0, 0, 0, 0],
    [8, 0, 10, 2, 18, 0, 0],
    [5, 10, 0, 3, 0, 16, 0],
    [0, 2, 3, 0, 12, 30, 14],
    [0, 18, 0, 12, 0, 0, 4],
    [0, 0, 16, 30, 0, 0, 26],
    [0, 0, 0, 14, 4, 26, 0]
]

The output will be:
{(0, 2, 5), (2, 3, 3), (3, 4, 12), (4, 6, 4), (2, 5, 16), (5, 6, 26)}

## How to Run
To run the script, simply execute the following into your terminal: python MST.py 

## License
This project is licensed under the MIT License.
