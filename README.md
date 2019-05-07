# Active Learning of Topology Properties on Streaming Graph
Statistical Framework for Streaming Graph Analysis

## Introduction

Social networks, a large and dynamic service, represent a large amount of information transfer over the Internet. Analysis of such networks is challenging due to the rapid changes of its members and their relationships. Also, in many cases, it is difficult to recompute the analytical results after every small modification. This problem can be avoided by considering an approach in which the time series and statistical techniques are used to quantitatively describe the temporal nature of a social network.
In order to develop higher-level, large-scale data analysis methods for classification, prediction, and anomaly detection, a solid foundation of analytical techniques are required. A streaming graph analysis model can be used to analyze real-time modifications in social media events.
To analyze Social media events, they can be represented as a graph in which people are vertices and edges connect two people representing the event between them. This graph model helps in real time prediction of new connection by computing vertex statistics which summarizes topological information.

## Approach

For the purpose of this project, we are using Streaming graph analysis model and a STINGER framework which enables easy operations of data graph analysis. We built our project in below-mentioned steps -

●	Firstly we built STINGER framework library into our working environment and test it for default graph by creating a server that updates graph for every 10 seconds.

●	Created a Twitter developer application to live stream trending hashtags into a JSON annotation that can be parsed into STINGER.

●	Afterward, we run different topology measurements on the created graph of Twitter users and their 2nd-degree connections

## Topological Properties

Network topology: It is the way in which the nodes and edges are arranged within a network.

Topological properties: It helps to identify relevant sub-structures within a network and can be applied to the network as a whole or to individual nodes and edges.
Few of the properties which we are using in our project are as follows -

1.	Centrality: It is measured for nodes and edges which gives the estimation of the importance of particular node/edge in terms of connectivity or information flow in the network.

2.	Betweenness Centrality: It is a measure of how often the node is a bridge between other nodes.
 
3.	Clustering Coefficients: It is a measure of the degree to which nodes in a graph tend to cluster together.

4.	Page Rank: PageRank is a link analysis algorithm and it assigns a numerical weighting to each element of a hyperlinked set of documents, such as the World Wide Web, with the purpose of "measuring" its relative importance within the set. The algorithm may be applied to any collection of entities with reciprocal quotations and references. The numerical weight that it assigns to any given element E is referred to as the PageRank of E.

5.	Eigenvector Centrality: It is a measure of the influence of a node in a network. It assigns relative scores to all nodes in the network based on the concept that connections to
high-scoring nodes contribute more to the score of the node in question than equal connections to low-scoring nodes.

## Results
