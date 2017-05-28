# Teaching-Pac-Man-to-Search

## Overview
In this lab, you will teach Pac-Man to search his world to complete the following tasks:

* find a single obstacle.
* find multiple obstacles.
* find the fastest way to eat all the food in the map.	

**Question 1 (2 points)** Implement the depth-first search (DFS) algorithm in the depthFirstSearch function in search.py. To make your algorithm complete, write the graph search version of DFS, which avoids expanding any already visited states (textbook section 3.5).

Your code should quickly find a solution for:

python pacman.py -l tinyMaze -p SearchAgent
python pacman.py -l mediumMaze -p SearchAgent
python pacman.py -l bigMaze -z .5 -p SearchAgent

**Results**:

### python pacman.py -l tinyMaze -p SearchAgent

[SearchAgent] using function depthFirstSearch
[SearchAgent] using problem type PositionSearchProblem
Path found with total cost of 8 in 0.0 seconds
Search nodes expanded: 15
Pacman emerges victorious! Score: 502
Average Score: 502.0
Scores:        502
Win Rate:      1/1 (1.00)
Record:        Win

### python pacman.py -l mediumMaze -p SearchAgent

[SearchAgent] using function depthFirstSearch
[SearchAgent] using problem type PositionSearchProblem
Path found with total cost of 68 in 0.0 seconds
Search nodes expanded: 269
Pacman emerges victorious! Score: 442
Average Score: 442.0
Scores:        442
Win Rate:      1/1 (1.00)
Record:        Win

### python pacman.py -l bigMaze -z .5 -p SearchAgent

Path found with total cost of 210 in 0.0 seconds
Search nodes expanded: 620
Pacman emerges victorious! Score: 300
Average Score: 300.0
Scores:        300
Win Rate:      1/1 (1.00)
Record:        Win

