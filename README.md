
MSN assignment 2 report.

The relationship between n and the diameter, probability and the diameter in the Erdős–Rényi model

Report prepared by Teaka Moaniba (ID: 107065436, NTHU – IMPISA)
For Professor Tung-Wei Kuo
 
Introduction
1.1.	Scope
The scope of this brief report will focus on observing on the Erdős–Rényi model using the computer generated graph approach.
1.2.	Purpose
The purpose of the observation is to determine the answer to the following questions: 
•	Consider the Erdős–Rényi model. What is the relationship between n and the diameter? (For example, diameter = n^0.5)
•	What is the relationship between p and the diameter? 
•	Give the intuition behind the answer and back up our argument with simulation results.  
Where n is the number of nodes and p is the probability of connected nodes in a graph.
1.3.	Background Information
There are several libraries and coding approaches which can be used to generate graph and carry out the observation on the G(n, p) model, but in this approach I will be using networkx and matplotlib libraries to generate graph in python.

Procedure
In this exercise, I use python Jupyter notebook to import the libraries mentioned above and then call the following functions:  
•	erdos_renyi_graph(n, p), 
•	fast_gnp_random_graph(n, p) 
•	and diameter(G) 
to generate  several  G(n, p) graphs and calculate their diameters. The detail method is stated below:
First, I generate the following graph under the following conditions: 
1)	Assuming n has a fixed value of 10 and p is the set of this values {0,  0.25,  0.5,  0.75, 1}.
2)	Assuming p has a fixed value of 0.8 and n is the set of this values {100, 500, 1000}.
3)	Assuming n has a fixed value of  50 and p is the set of this values {0.03, 0.04, 0.08, 0.1}.
Secondly, I computed each  diameter for every graph produced in each conditions above. 
Then, I plot two scatter charts (see fig 7.1 and 7.2 )  to show the trend between p over diameter and n over the diameter.
Finally I observed and compared the computed diameter in every conditions  for the visuals. 
 

