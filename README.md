# EF_Game
Ehrenfeucht-Frasse game to solve the NP hard problem of graph isomorphism

	In Computer Science, Graph isomorphism problem is the problem of determining whether 
	two finite graphs are isomorphic or not. If two graphs contain the same number of graph 
	vertices connected in the same way, then they are said to be isomorphic.
	
	This problem is of special interest in Computational Complexity Theory as it is 
	one of a very small number of problems belonging to NP(Nondeterministic Polynomial Time) 
	neither known to be solvable in polynomial time nor NP-Complete.
	
	To model the graph isomorphism problem, we tried to implement a simple GWAP (Game with a Purpose). 
	This was implemented using Unity3D. 
	
	The input to our game are two text files that represent the two graphs that need to be tested for
	isomorphism. The graphs must be given in a predefined format where the first line should 
	contain the word “NODE”. The next line contains the number of nodes followed by the edges 
	which are represented as a pair of nodes separated by a tab space in between them. 
	
	The output is determined by the player who wins. If the DUPLICATOR wins, 
	the two graphs are said to be isomorphic as he has successfully copied every 
	node in both the graphs. Conversely, if the SPOILER wins, the the graphs are not isomorphic.
