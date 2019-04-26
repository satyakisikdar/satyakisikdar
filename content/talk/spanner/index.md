+++
title = "Detecting Community Structures in Social Networks by Graph Sparsification"

date = 2016-03-01

authors = ["Partha Basuchowdhuri", "Satyaki Sikdar", "Sonu Shreshtha", "Subhashis Majumder"]

publication_types = ["2"]

abstract = "Community structures are inherent in social networks and finding them is an interesting and well-studied problem. Finding community structures in social networks is similar to locating densely connected clusters of nodes in a graph. One of the popular methods for finding communities is to first find the inter-community edges and then removing them to reveal the communities. It is well-known that a network centrality measure named edge betweenness can be used to detect the inter-community edges. The edges with high edge betweenness are those that fall in a large number of shortest paths out of all possible pairs of shortest paths. Finding all-pair shortest paths is a computationally expensive task, es-pecially for large-sized graphs. So we construct a t-spanner, a known graph sparsification technique, for finding edges with high betweenness and eventually find communities by removing such edges. Using the t-spanner, we then detect the inter-community edges within O(km) running time by building a distance oracle of size O(kn 1+ 1 k), where t = 2k-1. Compared to the traditional community detection methods dependent on calculation of betweenness values, our algo-rithm runs much faster. Experiments show that our algo-rithm finds communities of quality comparable to the other state-of-the-art community detection algorithms."
featured = false

publication = "*Proceedings of the 3rd IKDD Conference on Data Science, 2016*"

tags = ["Community Detection", "Modularity Maximization", "Social networks", "Spanner Construction", "community detection", "social network analysis", "spanner", "sparsification"]

url_pdf = "http://doi.acm.org/10.1145/2888451.2888479"
slides_pdf = "spanner.pdf"
doi = "10.1145/2888451.2888479"
+++

