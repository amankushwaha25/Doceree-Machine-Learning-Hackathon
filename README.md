# Machine Learning Hackathon (Doceree-TechGiG)
Welcome to the official repository for the machine learning model developed during the Doceree Hackathon hosted on TechGig! This repository showcases a Graph Neural Network (GNN) model that is specifically designed for classifying healthcare professionals based on searched keywords.

# Overview
In today's digital world, finding the right healthcare professional for a specific need can be a challenging task. To address this issue, our team participated in the Doceree Hackathon to develop an advanced machine learning model. The goal was to create an intelligent system capable of accurately categorizing healthcare professionals based on keywords entered in a search query.

# Model Description
The centerpiece of our solution is a Graph Neural Network (GNN) model. GNNs are a powerful class of machine learning models that can effectively capture complex relationships and dependencies within a graph-like structure. In our case, the healthcare professionals and their associated keywords form a graph-like network, and the GNN model is trained to learn from this network to perform accurate classification.
The model takes as input the keywords entered by the user in a search query and predicts the most relevant category of healthcare professionals based on these keywords. The training data used for the model development consists of labeled examples where keywords are mapped to their respective healthcare professional categories. We employed various techniques such as attention mechanisms and graph convolutional layers to enhance the model's ability to capture important keyword-context relationships.

# Graph Neural Network (GNN) for Graph Level Prediction
This repository contains code for training and using a Graph Neural Network (GNN) model to perform graph level prediction tasks. The GNN model is implemented using the PyTorch Geometric library and can be used to classify graphs based on their structural properties.

# Model Architecture
The GNN model architecture used in this project is a Graph Convolutional Network (GCN) with multiple layers. GCN is a popular GNN architecture that leverages message passing between nodes to capture graph structure. The model's architecture consists of two GCN layers followed by a linear layer for classification. The model can be customized and modified by adjusting the input dimensions, hidden dimensions, and output dimensions.

# Dataset
The dataset is cleaned and after preprocessing the data, we found that none of the other features affect much to the dependent feature than the keywords. The keywords are transformed to tensors and each graph represents a document or an instance, and the task is to predict the label associated with that graph. The dataset is preprocessed and transformed into a format compatible with PyTorch Geometric.

# License
This machine learning model is released under the MIT License. Feel free to use, modify, and distribute it according to the terms of the license.
