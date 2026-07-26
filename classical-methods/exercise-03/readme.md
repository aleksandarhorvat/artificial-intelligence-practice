# Exercise 3

## Overview

This exercise implements uninformed search algorithms (BFS, DFS, UCS) for the Romanian cities problem.

## Files

- `exercise_03.md` - problem statement for this exercise.
- `romanian_map_problem/` - complete solution directory.
  - `search_algorithms/` - search engine implementation.
    - `interfaces.py` - interfaces for problem formulation (from Exercise 2).
    - `problem.py` - base problem definition class (from Exercise 2).
    - `node.py` - node implementation used by search algorithms.
    - `search.py` - abstract search template.
    - `bfs.py` - Breadth-First Search implementation.
    - `dfs.py` - Depth-First Search implementation.
    - `ucs.py` - Uniform Cost Search implementation.
  - `city_connections.txt` - city connection data.
  - `straight_line_distances.txt` - straight-line distance data.
  - `romanian_map.py` - loader/model for Romanian map data.
  - `problem_definition.py` - Romanian cities problem definition.
  - `main.py` - entry point for running search algorithms.
