# Network-Properties-in-Spark-GraphFrames

Observed following network properties using pySpark, GraphFrames and networkX :

1) Implemented a function degreedist, which takes a GraphFrame object as input and computes the degree distribution of the graph. The function returns a DataFrame with two columns: degree and count.

2) Implemented a function closeness, which takes a GraphFrame object as input and computes the closeness centrality of every node in the graph. Determined the nodes that are important using this output.

3) Implemented a function articulations, which takes a GraphFrame object as input and finds all the articulation points of a graph. Articulation points, or cut vertices, are vertices in the graph that, when removed, create more components than there were originally
