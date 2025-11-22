# Exercise 3

In this exercise, uninformed search algorithms BFS, DFS, and UCS are implemented to solve the problem of Romanian cities.

## Files

- `exercise_03.md` - contains the text of the problem for this exercise
- `romanian_map_problem/` - this directory contains the solution of this exercise
    - `search_algorithms/` - this directory contains the implementation of the search algorithm engine used in this exercise
        - `interfaces.py` - this file contains the interfaces need for problem formulation (implemented on last exercise) 
        - `problem.py` - this file contains the class that encapsulates the problem definition (implemented on last exercise)
        - `node.py` - this file contains the implementation of the nodes used in the search algorithms
        - `search.py` - this file contains the abstract class defining the template for all search algorithms
        - `bfs.py` - this file contains the implementation of the BFS algorithm
        - `dfs.py` - this file contains the implementation of the DFS algorithm
        - `ucs.py` - this file contains the implementation of the UCS algorithm
    - `city_connections.txt` - file containing the connections between cities
    - `straight_line_distances.txt` - file containing the straight line distances between cities
    - `romanian_map.py` - this script defines the class which loads city data from the given files above
    - `problem_definition.py` - this file contains the implementation of the problem definition for the Romanian cities problem
    - `main.py` - this file contains the main function that runs the search algorithms on the problem
