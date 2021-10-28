# Articulation Point

A vertex is said to be an articulation point in a graph if removal of the vertex and its associated edges disconnects the graph. So, the removal of articulation points increases the number of connected components in a graph.

Articulation points are sometimes called cut vertices.

!["Articulation Point"](graph.JPG?raw=true)

Here we’ve got a graph G1 with a vertex set V = (A, B, C, D, E, F, G) and edge set E = (E1, E2, E3, E4, E5, E6, E7, E8, E9).
Let’s start with the vertex A and see if removing it and its and associated edges will disconnect the graph.

In this case, removal of vertex A and associated edges E1 and E3 doesn’t disconnect the graph. Therefore, A isn’t an articulation point.

But now let’s try vertex E and its associated edges E5, E6, E7, E8. This divides the graph G1 into two connected components:

The first component C1 with vertex set (F, G) and edge set (E9)
The second component C2 with vertex set (A, B, C, D) and edge set (E1, E2, E3, E4)

Thus, removing E satisfies the articulation point definition. Therefore, vertex **E** is an articulation point in graph G1.


# References :
https://www.baeldung.com/cs/graph-articulation-points
