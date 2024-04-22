# Prim-s-Algorithm
Prim's algorithm: Greedily selects vertices closest to the MST, forming a minimum spanning tree in a connected, undirected graph.

Prim's algorithm is a greedy algorithm used to find the minimum spanning tree (MST) of a connected, undirected graph. The idea is to grow the MST one vertex at a time, starting from an arbitrary vertex. At each step, the algorithm selects the vertex that is closest to the current MST, meaning it has the smallest edge weight connecting it to any vertex in the current MST.

Here's how the algorithm works:

Initialization:
Start with an empty set of vertices and an empty set of edges.
Choose an arbitrary vertex to start the MST.

Growing the MST:
Repeat the following steps until all vertices are included in the MST:
From the vertices not yet included in the MST, select the vertex v that is closest to any vertex u in the MST. This means finding the minimum weight edge (u, v) where u is in the MST and v is not.
Add vertex v to the MST and add edge (u, v) to the set of MST edges.

Termination:
The algorithm terminates when all vertices are included in the MST.

Output:
The output is the set of edges that form the MST.

DEMO:

![image](https://github.com/arshasuresh03/Prim-s-Algorithm/assets/160167081/86f06388-19b6-4a1b-be1e-3c520cb1d438)
