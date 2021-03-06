---
title: "Travelling Salesman Problem"
algorithmUrl: "https://github.com/eakyel/javascript-algorithms/blob/main/bfTravellingSalesman.js"
category: "Brute Force"
timeComplexity:
  normal: O(n!)
---

The travelling salesman problem (TSP) asks the following question: "Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city and returns to the origin city?"

![](/images/brute-force/travelling-salesman-problem/1.svg/)

Solution of a travelling salesman problem: the black line shows the shortest possible loop that connects every red dot.

![](/images/brute-force/travelling-salesman-problem/2.svg/)

TSP can be modelled as an undirected weighted graph, such that cities are the graph's vertices, paths are the graph's edges, and a path's distance is the edge's weight. It is a minimization problem starting and finishing at a specified vertex after having visited each other vertex exactly once. Often, the model is a complete graph (i.e. each pair of vertices is connected by an edge). If no path exists between two cities, adding an arbitrarily long edge will complete the graph without affecting the optimal tour.
