Download link :https://programming.engineering/product/hw5-minimum-spanning-tree/


# HW5-Minimum-Spanning-Tree
HW5: Minimum Spanning Tree
Q1. Say we had |V|-1 edges picked from a connected, weighted, and undirected graph. Are we guaranteed that these edges form a MST? Why or why not?

No, we are not guaranteed that these edges form a MST because there is no restriction on which edge to choose. This means that the sum of the edges might be greater than the MST weight.

Q2. Programming problem(submit a .java file) On a 2D-plane shown as below, some points with coordinates [xi, yi] are located. The cost of connecting two points [xi, yi] and [xj, yj] is the manhattan distance between them: |xi – xj| + |yi – yj|, where |val| denotes the absolute value of val.

Return the minimum cost and connected edges to make all points connected. You can use either Prim or Kruskal algorithm. Suppose the number of points is no more than 100. You don’t need to further improve the algorithm.

The coordinates can be Integer or Float (It doesn’t matter. Your code and test case can use Integer).

Example: Input Explanation:
