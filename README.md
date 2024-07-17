# SPGC
Graph Compression for Graph Neural Network Inference at Scale

This repository contains the code for the reproducibility of the experiments presented in the paper "Graph Compression for Graph Neural Network Inference at Scale". 
In this paper, we propose a novel inference-preserving graph compression (IPGC), a graph data compression scheme to scale GNNs inference.

## Organization of the code

All the code for the models described in the paper can be found in *codes/Cora.ipynb*, *codes/Arxiv.ipynb*, *codes/Yelp.ipynb*, *codes/Products.ipynb*, and *codes/MAG_Synthetic_Generator.ipynb*. 
We provide the datasets used in our experiments for users to validate our proposed methods located in: *Datasets.

## Prerequisites
Our code is based on Python3 (>= 3.11). The major libraries are listed as follows:
* NumPy (>= 1.26.3)
* Pandas (>= 2.0.1)
* Torch (>= 2.3.1)
* PyG (PyTorch Geometric) (>= 2.0.4)
* BisPy (>= 0.2.2)




