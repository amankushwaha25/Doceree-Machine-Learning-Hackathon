# Graph Neural Network (GNN) for Graph Level Prediction
This repository contains code for training and using a Graph Neural Network (GNN) model to perform graph level prediction tasks. The GNN model is implemented using the PyTorch Geometric library and can be used to classify graphs based on their structural properties.

# Model Architecture
The GNN model architecture used in this project is a Graph Convolutional Network (GCN) with multiple layers. GCN is a popular GNN architecture that leverages message passing between nodes to capture graph structure. The model's architecture consists of two GCN layers followed by a linear layer for classification. The model can be customized and modified by adjusting the input dimensions, hidden dimensions, and output dimensions.

# Dataset
The dataset is cleaned and after preprocessing the data, we found that none of the other features affect much to the dependent feature than the keywords. The keywords are transformed to tensors and each graph represents a document or an instance, and the task is to predict the label associated with that graph. The dataset is preprocessed and transformed into a format compatible with PyTorch Geometric.
