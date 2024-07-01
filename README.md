# LAB-machine-learning-introduction-to-machine-learning

![](https://user-images.githubusercontent.com/970858/63474771-d6734700-c469-11e9-83bb-9429da563909.png)

# Iris Classification Notebook

This repository contains a Jupyter notebook for classifying the Iris dataset using various classifiers. The notebook covers the entire process from data loading and preprocessing to model training and evaluation.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Notebook Contents](#notebook-contents)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project demonstrates the process of classifying the Iris dataset using different machine learning algorithms. It covers data preprocessing, model training, and evaluation using k-Nearest Neighbors (k-NN), Decision Tree, and Support Vector Machine (SVM) classifiers.

## Dataset

The Iris dataset is a classic dataset in the field of machine learning. It contains 150 instances of iris flowers with four features: sepal length, sepal width, petal length, and petal width. The goal is to classify the flowers into one of three species: Setosa, Versicolour, and Virginica.

## Setup Instructions

To run the notebook and reproduce the results, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone [TBD](https://github.com/codeskills-ai/LAB-machine-learning-introduction-to-machine-learning.git)
    cd LAB-machine-learning-introduction-to-machine-learning
    ```

2. **Create a virtual environment and onstall the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Start Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

5. Open the `iris.ipynb` notebook in Jupyter and run the cells to execute the code.

## Usage

The notebook is structured to guide you through the following steps:

1. **Loading the Dataset**:
    - Importing necessary libraries.
    - Loading the Iris dataset from `sklearn.datasets`.

2. **Data Preprocessing**:
    - Creating a DataFrame.
    - Scaling the features using `MinMaxScaler`.

3. **Splitting the Data**:
    - Splitting the dataset into training and testing sets using `train_test_split`.

4. **Training Classifiers**:
    - Training k-Nearest Neighbors (k-NN), Decision Tree, and Support Vector Machine (SVM) classifiers.

5. **Evaluating Classifiers**:
    - Evaluating the classifiers using accuracy scores with cross-validation.
    - Printing classification reports and confusion matrices.
    - Identifying and explaining correctly and incorrectly classified examples.

## Notebook Contents

### Sections Covered:

- **Introduction**: Overview of the notebook and its objectives.
- **Loading the Dataset**: Instructions to load and explore the Iris dataset.
- **Data Preprocessing**: Steps to preprocess the data.
- **Model Training**: Training various classifiers on the dataset.
- **Evaluation**: Evaluating the performance of the classifiers.
- **Examples**: Printing examples of correctly and incorrectly classified instances.

## Evaluation

The notebook includes detailed evaluation metrics for each classifier, including accuracy, precision, recall, F1-score, and confusion matrices. This helps in understanding the performance and potential areas for improvement for each model.

Happy Learning!
