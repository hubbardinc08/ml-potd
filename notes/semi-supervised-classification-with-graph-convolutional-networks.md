# SEMI-SUPERVISED CLASSIFICATION WITH GRAPH CONVOLUTIONAL NETWORKS

**Date**: 09-23-2026 • [Homebase](../README.md) • #field-tag

**Link:** https://arxiv.org/abs/1609.02907

### TL;DR:   
- Their motivation: classifying nodes in a graph where labels are only available for a small subset of nodes  
- 2 major contributions:  
	- Introduced a simple and consistent layer-wise propagation rule for graph-based neural networks  
	- Showed that graph-based neural networks can be used for semi-supervised classification of nodes in a graph


### Problem: 

### Key equations/terms: 

### Design choices + why: 

### Results: 


### Open questions: 

**Builds on:**   
**Rating:** ⭐️⭐️⭐️

---  
#### Notes for myself:

**Semi-supervised learning:** a small group of labeled data is first used to train the model. Then a larger group of unlabeled data is used for classification/prediction, and pseudo-labels are generated for the highest-scoring predictions. These samples are added to the original labeled group, and then the model is trained again on the concatenated dataset.

**Graph-structured data:** data that contains clear nodes and connections (edges) between nodes  
- For instance, citation networks can be treated as a graph where the nodes are documents


#### Laplacian regularization:  
**Key idea:** if two data points are similar, encourage the model to make similar predictions on both

Unlike parameter regularization (ridge, lasso are both) where data that don't fit a certain connected model are penalized, Laplacian regularization penalizes differing predictions on similar data
