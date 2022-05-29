## Multi label text classification using Graph Convolution Network
Many studies have recently concentrated on determining if GCNs can handle various Natural Language Processing tasks, particularly text categorization. While text classification using GCNs is widely-studied, its graph building approaches, such as node/edge selection and feature
representation, as well as the best GCN learning mechanism in text classification, are mostly ignored. <br> This project aims to carry out a multi label text classification process with the help of node classification and by utilizing graph convolution network (GCN).

## Flow Diagram
![diagram](https://user-images.githubusercontent.com/65306299/170878432-19d6e50c-ea1c-4416-9049-71d287a1a2ca.png)

## About the Dataset
1. The dataset used for our project is BBC News dataset which was taken from kaggle.
2. The dataset has 2225 articles
3. The dataset consists of two columns : text and category
4. Each category pertains to its own type of news articles.
5. Each labeled under one of 5 categories: business, entertainment, politics, sport or tech

## Workflow
1. Preprocessing
2. Keyword extraction 
3. Constructing word-word and word-doc edges
4. Building the graph
5. Model Building
6. Training using GCN
7. Evaluation of the model
