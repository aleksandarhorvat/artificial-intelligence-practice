Implement the informed search algorithms (GBFS and A*) for the word rearrangement game (Word Game).
Define an appropriate heuristic function (the same one will be used by both algorithms) and implement it.
Pay attention to the fact that the heuristic function must be admissible and (preferably) monotonic.

The Word Game starts from a given initial word, and the goal is to reach the target word.
In each move, two letters in the word are selected and their positions are swapped.
The cost of each move is the same and equals 1.
Optimality is achieved by reaching the target word in the smallest possible number of moves.

Add functionality to count the number of states each algorithm visits in order to reach the correct solution, and compare these numbers for the two search algorithms.

Example:
Initial word: FTRIAICAIL
Target word: ARTIFICIAL
One possible solution is:
FTRIAICAIL → ATRIFICAIL → ARTIFICAIL → ARTIFICIAL