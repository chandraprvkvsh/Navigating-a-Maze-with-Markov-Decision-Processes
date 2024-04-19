# Brief Introduction

Objective of this project was to illustrate the use of Value iteration technique for Markov Decision Processes
This project involved a custom environment created by me which is a 5x5 grid world where a mouse wants to reach cheese and it can take actions in 4 directions UP, DOWN, LEFT and RIGHT. Best policy is found while maximizing reward.
This project is from scratch(only NumPy, Pandas are used).

# Details about the project

A mouse is on a 5 X 5 maze and its goal is to reach the cheese

The mouse can take actions in each direction  (UP=0, RIGHT=1, DOWN=2, 
LEFT=3). 

Model of the maze environment, wherein the states are defined is provided for your reference.  
Any action that takes the mouse beyond the maze will result in the mouse staying in the same state.
Mouse receives a reward of -1 at each step until it reaches the cheese block.

Carry out the following tasks:

1.  Find an optimal  policy through Value  Iteration method that takes the 
         
       mouse to the cheese block starting from any internal state.

2.  Print the optimal policy to reach the cheese block.

3.   Print your output to a csv file.


