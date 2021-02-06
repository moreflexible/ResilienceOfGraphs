# GraphTheory - Resilience of Weighted Networks

## K-Regular Networks vs Scale Free Networks

In this project we tried to analyze resilience of weighted networks and resilience is defined as a system’s ability  to retain its basic functionality when errors, failures, and environmental changes occur. It is a crucial property of many networked systems.

There are too many metrics to measure it but we gonna focus on largest connected component size so we are able to see how structure percolates and another metric we used, the global efficiency which will provide us to see efficiency of network globally even if network is separated to  multiple components.

Most of the previous works , generally focused on mostly local properties of graphs to measure resilience.

### We have chosen two different network type for analyze. 
    - First one K-Regular, an homogeneous  network in which every member has equal link.
    - The other one is Scale Free networks in which most of nodes have one or two links and some of them has most of the links as hubs like internet.

### If you ask what these edges and nodes represent ?

You can think of these graphs as computer network and the nodes represent routers and switches so the edges will represent cables carrying the information and data. 
So how we assign weights to the edges ?

    - Weights will reflect the capacity of each edge (you can think of the capacity as quantity of information flows). 
    - So we measure this capacity using edge betweenness centrality then normalize it.
    - If we measure the global efficiency with this weight distribution, higher weights will be avoided by shortest path algorithm so we take reciprocal of edge.












