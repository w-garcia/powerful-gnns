# Distance Constraint-based Characterization of the Graph Isomorphism Network

This repository is a fork of the code by [Xu et al.](https://github.com/weihua916/powerful-gnns)

We run some experiments using their code to give a distance constraint-based characterization of Graph Isomorphism Network (GIN). 

## Installation
Install PyTorch following the instuctions on the [official website](https://pytorch.org/). The code has been tested over PyTorch 1.4.0. 

Then install the other dependencies.
```
pip install -r requirements.txt
```

## Experiments

The main experiments were ran from `distance_experiments-mutag.ipynb` and `distance_experiments-proteins.ipynb`, for the MUTAG and PROTEINS datasets, respectively. `debug.ipynb` contains some boilerplate code which was used to debug the experiment implementations. 
