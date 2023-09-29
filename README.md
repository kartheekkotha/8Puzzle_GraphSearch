# Eight Puzzle Solver

This repository contains a Python implementation of the Eight Puzzle problem, along with various search algorithms to find a solution from an initial state to a goal state.

## Puzzle Class

The `Puzzle` class represents the Eight Puzzle problem. The initial state is a 3x3 grid with 8 movable tiles and one blank square. The goal is to reach the configuration `1 2 3 4 5 6 7 8`. The puzzle states can be represented as strings, where the blank is symbolized by `0`. The class provides methods to transition from one state to another, and a `play()` method to make random moves.


## Search Algorithms

The repository also implements various search algorithms to find a solution to the Eight Puzzle problem:

1. Depth First Search (`depth_first_search`)
2. Breadth First Search (`breadth_first_search`)
3. Depth Limited Search (`depth_limited_search`)
4. Iterative Deepening Search (`iterative_deepening_search`)



## Heuristic Search

The repository includes functions to apply heuristic search algorithms:

1. Greedy Search
2. A* Search



## Instructions

1. Clone this repository.
2. Use the provided classes and functions to solve the Eight Puzzle problem and apply heuristic search.
3. Adjust parameters and initial states as needed.
