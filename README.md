# Pathfinding Algorithms: Dijkstra and BFS

This repository contains implementations of two popular pathfinding algorithms: Dijkstra's algorithm and Breadth-First Search (BFS). Both algorithms are used to find the shortest path between two points in a grid-based environment with obstacles.

## Overview

- **Dijkstra's Algorithm**: This algorithm finds the shortest path between two points by assigning a cost to each step and choosing the path with the lowest total cost. It is particularly useful when the cost of moving between nodes varies.

- **Breadth-First Search (BFS)**: BFS explores all nodes at the current level before moving to the next level. It is simpler than Dijkstra's and is used when all movements have the same cost.

## Libraries Used

- **NumPy**: For numerical computations.
- **SortedCollections**: For maintaining ordered sets.
- **Matplotlib**: For creating polygon objects.
- **Pygame**: For visualizing the path.
- **Queue**: For BFS implementation.
- **PriorityQueue**: For Dijkstra's implementation.

## How to Run

1. **Install Required Libraries**:

2. **Run Dijkstra's Algorithm**:
- python3 dijkstra_Amogha_Sunil.py
- Run the script and follow the prompts to input start and goal positions.

3. **Run BFS Algorithm**:
- python3 bfs_Amogha_Sunil.py
- Run the script and follow the prompts to input start and goal positions.

## Basic Information

- **Grid Size**: The environment is a 1800x500 grid.
- **Obstacles**: Defined by polygons representing letters and numbers.
- **Path Visualization**: Uses Pygame to display the shortest path.

