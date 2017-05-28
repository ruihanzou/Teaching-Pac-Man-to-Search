# Teaching-Pac-Man-to-Search

## Overview
In this lab, you will teach Pac-Man to search his world to complete the following tasks:

* find a single obstacle.
* find multiple obstacles.
* find the fastest way to eat all the food in the map.	

**Question 1 (2 points)** Implement the depth-first search (DFS) algorithm in the depthFirstSearch function in search.py. To make your algorithm complete, write the graph search version of DFS, which avoids expanding any already visited states (textbook section 3.5).

Your code should quickly find a solution for:<br />

python pacman.py -l tinyMaze -p SearchAgent<br />
python pacman.py -l mediumMaze -p SearchAgent<br />
python pacman.py -l bigMaze -z .5 -p SearchAgent<br />

**Results**:

### python pacman.py -l tinyMaze -p SearchAgent

[SearchAgent] using function depthFirstSearch<br />
[SearchAgent] using problem type PositionSearchProblem<br />
Path found with total cost of 8 in 0.0 seconds<br />
Search nodes expanded: 15<br />
Pacman emerges victorious! Score: 502<br />
Average Score: 502.0<br />
Scores:        502<br />
Win Rate:      1/1 (1.00)<br />
Record:        Win<br />

### python pacman.py -l mediumMaze -p SearchAgent<br />

[SearchAgent] using function depthFirstSearch<br />
[SearchAgent] using problem type PositionSearchProblem<br />
Path found with total cost of 68 in 0.0 seconds<br />
Search nodes expanded: 269<br />
Pacman emerges victorious! Score: 442<br />
Average Score: 442.0<br />
Scores:        442<br />
Win Rate:      1/1 (1.00)<br />
Record:        Win<br />

### python pacman.py -l bigMaze -z .5 -p SearchAgent<br />

Path found with total cost of 210 in 0.0 seconds<br />
Search nodes expanded: 620<br />
Pacman emerges victorious! Score: 300<br />
Average Score: 300.0<br />
Scores:        300<br />
Win Rate:      1/1 (1.00)<br />
Record:        Win<br />

