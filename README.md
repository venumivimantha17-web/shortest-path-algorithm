# Shortest Path Algorithm in Python

This project implements a shortest path algorithm in Python using an adjacency matrix.

The algorithm calculates the shortest distance from a starting node to a target node and also keeps track of the path taken to reach the destination.

## Features

- Uses an adjacency matrix to represent the graph.
- Calculates shortest distances between nodes.
- Tracks the actual shortest path.
- Supports finding a path to a specific target node.
- Can also calculate shortest paths to all reachable nodes.
- Uses `float('inf')` to represent unreachable nodes.

## Example

For the provided graph, the algorithm finds the shortest path from node `0` to node `5`.

**Output:**

```text
0-5 distance: 5
Path: 0 -> 2 -> 1 -> 5
