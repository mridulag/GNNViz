# GNNViz

In this visualization, we intend to make Graph Neural Network (GNN - machine learning framework used for semi-supervised classification of graph networks) more transparent by visualizing and its weights and featureset at different levels during training.

For this demo, we used Mutag dataset, a well known benchmark dataset for graph processing algorithms. https://rdrr.io/cran/graphkernels/man/mutag.html


![Figure 1](https://github.com/mridulag/GNNViz/blob/master/Snapshots/GNN-k1.png "Figure 1")
The slide (on the top of graph) represents the kth layer of GNN.  The graph (on the left) has 17 nodes and 38 edges. The table (in the middle) represents the feature set, based on the classification of nodes into 3 classes. Using the feature set and the neighbouring nodes, model first learns an aggregated 7 feature representation.


![Figure 2](https://github.com/mridulag/GNNViz/blob/master/Snapshots/GNN-K2.png "Figure 2")



![Figure 3](https://github.com/mridulag/GNNViz/blob/master/Snapshots/GNN_withWeights_v1.png "Figure 3")
