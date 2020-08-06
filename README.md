# Maze Solver


##Breadth-First Search


## Greedy Best-First Search
A search algorithm that expands the node that is closest to the goal, as estimated by
a heuristic function h(n).

A heuristic function h(n) is chose to be Manhattan distance of the goal and the
 current position.

## A * search
search algorithm that expands node with lowest value of g(n) + h(n), where  
g(n) = cost to reach node
h(n) = estimated cost to goal


g(n) is choose to

optimal if
- h(n) is admissible (never overestimates the true cost), and
- h(n) is consistent(for every node n and successor n' with step cost c, h(n) \leq h(n') + c)



## Adversarial Search  

## Minimax
good for deterministic game where 2 player is involved.
For example a
s_0 : initial state  
Players(s) : return which player to move in state s  
Actions(s) : returns legal moves in state s  
Result(s,a) : return state after action a taken in state s  
Terminal(s) : checks if state s is a terminal state
Utility(s) : final numerical value for terminal state s
