# Investigating Convex Neural Networks: An Implementation Repository

## Introduction

Welcome to the repository for investigating Convex Neural Networks (CNNs) as outlined in the research paper titled "Investigating Convex Neural Networks". Here, you'll find the implementation of neural network architectures and experiments discussed in the paper, allowing for result replication and further exploration.

## Overview

The research delves into the performance analysis of Input Output Convex Neural Networks (IOC-NN) in comparison to conventional Neural Networks (NN) across a spectrum of datasets and architectures. The study primarily focuses on three main architectures: Multi-Layer Perceptron (MLP), AllConv, and DenseNet, along with their IOC counterparts.

## Notebooks

### Notebook 1: MLP and IOC-NN on CIFAR-10 and MNIST

This notebook showcases experiments conducted on basic MLP and its IOC counterpart using CIFAR-10 and MNIST datasets. Key experiments include:
- Training MLP and IOC-NN architectures on CIFAR-10
- Utilizing duplicate-free data (ciFAIR10)
- Ensembles of Binary Experts
- Boosted Ensemble
- Implementing similar architectures on the MNIST dataset

### Notebook 2: AllConv and IOC-AllConv for CIFAR-10

This notebook exhibits experiments conducted on the baseline AllConv architecture and its IOC counterpart using the CIFAR-10 dataset. Key experiments include:
- Training AllConv and IOC-AllConv architectures on CIFAR-10
- Utilizing duplicate-free data (ciFAIR10)
- Partially randomized labeling
- Boosted Ensemble

### Notebook 3: DenseNet and IOC-DenseNet for CIFAR-10

This notebook demonstrates experiments conducted on the baseline DenseNet architecture and its IOC counterpart using the CIFAR-10 dataset. Key experiments include:
- Training DenseNet and IOC-DenseNet architectures on CIFAR-10
- Utilizing duplicate-free data (ciFAIR10)
- Boosted Ensemble

## Experimentation Details

The experiments detailed in the research paper encompass the following aspects:

- **Datasets and Architectures**: Training MLP, AllConv, and DenseNet architectures on various datasets including MNIST, FMNIST, STL-10, SVHN, CIFAR-10, and CIFAR-100. Architectures incorporate batch normalization, ReLU/ELU activations, softmax in the last layer, and the Adam optimizer.

- **Training on Duplicate-Free Data**: Training on ciFAIR10 and ciFAIR100 datasets where duplicate images in the test sets are substituted with new images.

- **Training IOC Architectures**: Enforcing convexity constraints by exponentiating negative weights and making modifications in activations, input transformation, and learning rate decay.

- **Training Ensembles of Binary Experts**: Training an ensemble of IOC-MLP on CIFAR-10 dataset categorized into 'Animal' and 'Not Animal' classes.

- **Training Boosted Ensembles**: Training boosted ensembles with a gating network using bootstrapping mechanisms.

- **Partially Randomized Labeling**: Investigating IOC-NN's behavior in the presence of partial label noise on CIFAR-10 dataset.

## Conclusion

This repository offers a comprehensive implementation of experiments elucidated in the research paper. The provided notebooks serve as valuable resources for replication, further experimentation, and exploration of IOC-NN architectures.

---

Let me know if you need any further refinements or additions to the readme file!
