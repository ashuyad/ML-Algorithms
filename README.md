# ML Algorithms

A collection of machine-learning notebooks and experiments implemented in Python. Each project lives in its own directory and explores an algorithm or technique, often with a sample dataset.

> **Purpose:** learning and experimentation. Results and code may need adaptation before use in production.

## Projects

| Project | Description |
| --- | --- |
| [Apriori](Apriori/) | Frequent itemset mining and association-rule learning. |
| [Bag-of-Word Algorithm](Bag-of-Word-Algorithm/) | Text representation using the bag-of-words approach. |
| [CATBoost](CATBoost/) | Gradient boosting with CatBoost. |
| [Customer Churn using ANN](Customer-Churn-using-ANN/) | Customer churn prediction with an artificial neural network. |
| [Grid Search](Grid-Search/) | Model hyperparameter tuning with grid search. |
| [Hierarchical Clustering](Hierarchical-Clustering/) | Unsupervised clustering with a hierarchical method. |
| [Image Classification using CNN](Image-Classification-using-CNN/) | Image classification with a convolutional neural network. |
| [K-fold Cross-Validation](K-fold-Cross-Validation/) | Model evaluation by splitting data into *k* folds and rotating the validation fold. |
| [Kernel PCA](Kernel-PCA/) | Nonlinear dimensionality reduction using kernel principal component analysis. |
| [Linear Discriminant Analysis](Least-Discriminant-Analysis/) | Dimensionality reduction and classification with discriminant analysis. |
| [MNIST ANN (PyTorch)](MNIST-ANN%28Pytorch%29/) | Neural-network experiments on the MNIST dataset using PyTorch. |
| [Principal Component Analysis](Principal-Component-Analysis/) | Dimensionality reduction using PCA. |
| [PyTorch RNN](Pytorch-RNN/) | Recurrent neural network experiments using PyTorch. |
| [Thompson Sampling](Thompson-Sampling-Algorithm/) | A multi-armed bandit strategy for balancing exploration and exploitation. |
| [Upper Confidence Bound](Upper-Confidence-Bound/) | A multi-armed bandit strategy based on confidence bounds. |
| [XGBoost](XGBoost/) | Gradient-boosted decision trees using XGBoost. |

## Getting started

1. Clone the repository:

   ```bash
   git clone https://github.com/ashuyad/ML-Algorithms.git
   cd ML-Algorithms
   ```

2. Install Jupyter if it is not already available in your Python environment:

   ```bash
   python -m pip install jupyter
   ```

3. Start Jupyter and open the notebook in the project directory you want to explore:

   ```bash
   jupyter notebook
   ```

Individual notebooks may require additional libraries. Check the imports and any project-specific `requirements.txt` before running a notebook. Some projects include datasets in their directories; follow the notebook's instructions for any data it expects.

## Suggested workflow

- Start with a project directory and read through its notebook from top to bottom.
- Run the cells in order, and inspect the data preparation, model, and evaluation steps.
- Experiment with parameters or datasets, and compare the results.
