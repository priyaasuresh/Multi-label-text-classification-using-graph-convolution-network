# Multi-Label Text Classification using Graph Convolutional Networks (GCNs)

## Problem Statement
Many studies have recently concentrated on determining if GCNs can handle various Natural Language Processing tasks, particularly text categorization. While text classification using GCNs is widely-studied, its graph building approaches, such as node/edge selection and feature
representation, as well as the best GCN learning mechanism in text classification, are mostly ignored. <br> This project aims to carry out a multi label text classification process with the help of node classification and by utilizing graph convolution network (GCN).

## Flow Diagram
![diagram](https://user-images.githubusercontent.com/65306299/170878432-19d6e50c-ea1c-4416-9049-71d287a1a2ca.png)


## Project Uniqueness

- **Graph Construction**: Building graphs using both document-word edges and word-word edges.
- **GCN Utilization**: Employing GCNs for multi-label text categorization.
- **Insightful Analysis**: Provides valuable information on the effectiveness of different graph node/edge building methods in GCN training/testing for text classification.

## Dataset

- **Source**: BBC News dataset from Kaggle.
- **Articles**: 2225 articles.
- **Categories**: Business, Entertainment, Politics, Sport, Tech.
- **Columns**: Text and Category.

## Visualisation

- **Node Categorization**: Visualization of node categorization for each text column in the CSV file.
- **Document Nodes**: Nodes representing documents.
- **Word Nodes**: Nodes representing words.

  ![image](https://github.com/user-attachments/assets/e67a87eb-9768-42bd-9824-eed9975e0471)


### Visualizations

1. **Confusion Matrix**  
   <img width="404" alt="image" src="https://github.com/user-attachments/assets/417059cc-d686-45d6-8e85-de9d482b5e94">


3. **Plot of Number of Epochs vs. Cross-Entropy Loss**  
   <img width="468" alt="image" src="https://github.com/user-attachments/assets/7565cf74-8374-4973-bee5-5600dcd54904">


## Evaluation Metrics

- **Confusion Matrix**
- **F1 Scores (Macro)**: 0.9295
- **F1 Scores (Weighted)**: 0.9318
- **Accuracy**: 0.9318

## Code Functionality

| No | Code Functionality | % Complete | Runs without Problem (Y/N) | Minor Issues |
|----|---------------------|------------|----------------------------|--------------|
| 1  | Preprocessing       | 100        | Y                          | None         |
| 2  | Keyword Extraction  | 100        | Y                          | None         |
| 3  | Constructing Edges  | 100        | Y                          | None         |
| 4  | Building the Graph  | 100        | Y                          | None         |
| 5  | Model Building      | 100        | Y                          | None         |
| 6  | Training using GCN  | 100        | Y                          | None         |
| 7  | Evaluation          | 100        | Y                          | None         |

## Top Learnings

1. Building graphs using text data.
2. Performing node classification.
3. Graph node and edge construction.
4. The role of nodes and edges in corpus-level textual graphs.
5. The impact of node embeddings, edge construction, and GCN learning.

## Top Unresolved Challenges

1. **Model Accuracy**: Improving model accuracy beyond the current 93%.
   - *Challenge Type*: Others (models to be tried out)
2. **Graph Building Efficiency**: Finding better approaches for constructing graphs to enhance efficiency.
   - *Challenge Type*: Others
