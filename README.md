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
