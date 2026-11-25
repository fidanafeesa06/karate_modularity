# karate_modularity
# Modularity on the Karate Club Graph

**DSC212: Graph Theory, Research Assignment**

**Name:** Fida Nafeesa | **Roll No:** IMS25079

## About
This project finds communities in Zachary's Karate Club network using recursive spectral modularity bisection, implemented from scratch with NumPy and NetworkX. After every split it draws the graph with each community in a different colour and tracks four node metrics: degree centrality, betweenness centrality, closeness centrality and clustering coefficient.


## Results
- The algorithm finds 5 communities with final modularity Q = 0.4094.
- The first split matches the real club split for 33 of 34 members (only node 8 differs).
- Nodes 0, 33 and 32 stay the most central across all splits.

## Reference
M. E. J. Newman, "Modularity and community structure in networks," PNAS 103(23), 8577-8582 (2006).
DSC212 ASSIGNMENT: SPECTRAL MODULARITY ON THE KARATE CLUB GRAPH
