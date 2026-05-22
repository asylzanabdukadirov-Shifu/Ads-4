
# Graph Traversal and Dijkstra Algorithm

## Overview

This project demonstrates the implementation of several graph algorithms in Java using an adjacency list representation.

The project includes:

* Breadth-First Search (BFS)
* Depth-First Search (DFS)
* Dijkstra’s Shortest Path Algorithm

The program also compares traversal execution times on graphs of different sizes.

---

## Graph Structure

The graph is implemented using:

* `HashMap`
* `ArrayList`
* Weighted edges
* Adjacency List representation

Each vertex is connected through edges that can store weights for shortest path calculations.

---

## Bonus Task Implementation

For the bonus task, the graph was upgraded to support weighted edges and shortest path calculations.

### Changes Made

* Added a `weight` field to the `Edge` class
* Modified the adjacency list to store `Edge` objects instead of integers
* Updated graph connections to support edge weights
* Implemented Dijkstra’s Algorithm using arrays, loops, and collections
* Added shortest path output from a selected starting vertex

---

## Dijkstra Algorithm

The `dijkstra(int start)` method:

* Takes a starting vertex
* Calculates the shortest distance to all other vertices
* Displays the results in the console

The implementation does not use a priority queue, following the bonus task requirements.

---


## Technologies Used

* Java
* HashMap
* ArrayList
* Queue
* Set

---

## Author

Student project for graph traversal and shortest path algorithm implementation.









# Assignment 4: Graph Traversal and Representation System

## Project Overview

This project demonstrates the implementation of graph data structures and graph traversal algorithms in Java.  
The graph is represented using an adjacency list structure. The program supports Breadth-First Search (BFS) and Depth-First Search (DFS) traversals and compares their execution times on graphs of different sizes.

The project was developed using object-oriented programming principles with separate classes for vertices, edges, graph management, and experiments.

---

# Graph Concepts

A graph is a collection of:

- Vertices (nodes)
- Edges (connections between vertices)

Example:

1 → 2  
1 → 3  
2 → 4

In this project, graphs are stored using an adjacency list representation.

---

# Classes Description

## Vertex Class

The `Vertex` class represents a node in the graph.

### Fields
- `id` — unique identifier of the vertex

### Methods
- Constructor
- `getId()`
- `toString()`

---

## Edge Class

The `Edge` class represents a connection between two vertices.

### Fields
- `source`
- `destination`

Methods
- Constructor
- Getters
- `toString()`

---

## Graph Class

The `Graph` class manages the graph structure using an adjacency list.

### Features
- Add vertices
- Add edges
- Print graph structure
- BFS traversal
- DFS traversal

### Adjacency List Example

```text
1 -> [2, 3]
2 -> [1, 4]
3 -> [1]
