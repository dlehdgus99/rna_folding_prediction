# RNA Folding Prediction with Graph Neural Networks

This project demonstrates the application of Graph Neural Networks (GNNs) for predicting RNA folding patterns. Utilizing the `torch_geometric` library, the notebook outlines the steps from data preprocessing, defining the graph structure, to training a GNN model and evaluating its performance.

## Overview

- **Adjacency Definition**: Introduction to creating graph structures for RNA sequences.
- **Data Loader Definition**: Implementation of a data loading mechanism for handling RNA sequence data.
- **Data Handling**: Preprocessing steps to convert RNA data into a format suitable for GNN models.
- **Loss and Metrics**: Details on the loss function used for training and metrics for model evaluation.
- **Model Architecture**: Description of the GNN model used for RNA folding prediction.
- **Training Process**: Explanation of the training procedure, including data splitting and optimization techniques.
- **Model Evaluation**: Methods to assess the predictive performance of the GNN model.

## Setup and Installation

1. Ensure Python 3.x and PyTorch are installed.
2. Install required libraries: `pip install torch_geometric ViennaRNA`.

## Data Preprocessing

- Instructions on converting CSV data to Parquet format for efficient processing.
- Steps to prepare and structure the RNA sequence data for GNN input.

## Model Details

- Explanation of the GNN architecture designed for RNA folding prediction.
- Description of adjacency matrices, feature engineering, and other graph-based inputs.

## Training the Model

- Details on the training setup, including loss functions, optimization algorithms, and hyperparameters.

## Evaluation and Insights

- Techniques for evaluating the model's performance.
- Visualization and analysis of the model's predictive capabilities on test data.

## Conclusion

- Summary of the project's outcomes and potential areas for future research and improvement.
