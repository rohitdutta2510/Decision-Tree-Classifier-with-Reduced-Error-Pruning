# Decision Tree Classifier from scratch with Reduced Error Pruning

This repository contains a Python implementation of a Decision Tree Classifier, following the standard ID3 algorithm, which uses Information Gain as the criterion for splitting the data at each node. The project is structured as an academic assignment, aiming to provide hands-on experience with decision trees, including their construction, evaluation, and optimization through pruning.

## Overview

Decision trees are powerful graphical models used for both classification and regression tasks. They simplify decision-making by breaking down data into smaller subsets using feature-based questions, represented in a tree-like structure. This implementation focuses on classification tasks, aiming to provide an interpretable and effective method for data partitioning and decision-making.

## Assignment Instructions

### Task Overview

1. **Data Preparation**:
   - Split the dataset into training (80%) and testing (20%) sets.
   - Normalize or regularize the data if necessary.
   - Encode categorical variables using an appropriate method if necessary.

2. **ID3 Algorithm Implementation**:
   - Implement the ID3 Decision Tree algorithm as discussed in class.
   - Use Information Gain to determine the best attribute for splitting at each node.
   - Stop splitting a node if it contains less than 10 data points.
   - **Important**: Do not use the scikit-learn library for this part of the assignment.

3. **Reduced Error Pruning**:
   - Perform reduced error pruning on the decision tree obtained from step 2.
   - Plot a graph showing the variation in test accuracy with varying tree depths.
   - Print the pruned tree in a hierarchical fashion, clearly showing attributes at each level.

4. **Evaluation Metrics**:
   - Report the mean macro accuracy, macro precision, and macro recall for the classifier.
   - You may use scikit-learn implementations for computing these metrics, but it is not mandatory.

## Requirements

- Python 3.6 or later.
- NumPy (for data manipulation).
- Matplotlib (for plotting graphs).
- (Optional) scikit-learn (only if using its implementations for evaluation metrics).

## Installation

To set up your environment for running the decision tree classifier, follow these steps:

```bash
git clone <repository-url>
cd <repository-directory>
pip install numpy matplotlib
# Optional: Install scikit-learn if you plan to use it for metrics
pip install scikit-learn
