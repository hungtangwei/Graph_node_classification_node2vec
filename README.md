# Graph_node_classification_node2vec
Perform the node classification in graph dataset

## Description
perform the node classification by using the graph dataset of citation network. In this dataset, each node is paper, and edge indicates the relationship between two paper. And then I will perform the node embedding and the text embedding. Finally, I will build two SVM classifier, one is with node embedding, another is with node embedding + text embedding, and to evaluate these two SVM models by accuracy.

## Dataset Description
In this network, each node is paper, an edge indicates the relationship between two papers. As the network has extremely sparse network structure, we also provide text information for each paper, i.e., the title of each paper. The files in the dataset include:

- docs.txt: Title information of each node in a network, each line represents a node (paper). The first item in each line is the node ID.
- adjedges.txt: Neighbor nodes of each node in a network. The first item in each line is the node ID, and the rest items are nodes that have a link to the first node. Node that if only one item in a line, it means that the node has no links to other nodes.
- labels.txt: Class labels of a node. Each line represents a node id and its class label

## Authors

Tangwei, Hung

## Contact
hung.tangwei@gmail.com

