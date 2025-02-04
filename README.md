# LAB-machine-learning-introduction-to-machine-learning

![](https://user-images.githubusercontent.com/970858/63474771-d6734700-c469-11e9-83bb-9429da563909.png)

# Classification Notebooks

This repository contains two Jupyter notebooks. The first one for classifying the Iris dataset using various classifiers. The notebook covers the entire process from data loading and preprocessing to model training and evaluation. The second one introduces an exercise to classify medical data for cancer detection.

## Table of Contents

- IRIS Dataset
    - [Introduction](#introduction)
    - [Dataset](#dataset)
    - [Setup Instructions](#setup-instructions)
    - [Usage](#usage)
    - [Notebook Contents](#notebook-contents)
    - [Evaluation](#evaluation)
- Breast Cancer Dataset
    - [Introduction](#breast-cancer)

# IRIS

## Introduction

This project demonstrates the process of classifying the Iris dataset using different machine learning algorithms. It covers data preprocessing, model training, and evaluation using k-Nearest Neighbors (k-NN), Decision Tree, and Support Vector Machine (SVM) classifiers.

## Dataset

The Iris dataset is a classic dataset in the field of machine learning. It contains 150 instances of iris flowers with four features: sepal length, sepal width, petal length, and petal width. The goal is to classify the flowers into one of three species: Setosa, Versicolour, and Virginica.

## Setup Instructions

To run the notebook and reproduce the results, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/codeskills-ai/LAB-machine-learning-introduction-to-machine-learning.git
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

## Evaluation

The notebook includes detailed evaluation metrics for each classifier, including accuracy, precision, recall, F1-score, and confusion matrices. This helps in understanding the performance and potential areas for improvement for each model.

# Breast Cancer

This exercise can be developed using **Obviously AI** or the provided notebook. Alternatively, students can choose to complete it using both methods.

This notebook provides a comprehensive guide to classifying breast cancer cases using the Breast Cancer Wisconsin dataset. The main goals are for students to preprocess the data, apply various machine learning algorithms, and evaluate their performance, while also exploring advanced models like Random Forest and Gradient Boosting on their own.

---

### Objective

#### Using the Notebook
The goal of this lab is to train a classification model using Python and Jupyter Notebook to predict whether a tumor is malignant or benign based on features extracted from digital biopsy images. Through this exercise, you will learn how to preprocess data, train machine learning models, and evaluate their performance using metrics like accuracy, precision, recall, and F1-score.

#### Using Obviously AI
The goal of this lab is to train a classification model using **Obviously AI**, a no-code AutoML platform, to predict whether a tumor is malignant or benign. Through this exercise, you will learn how to upload a dataset, train a model without writing code, and evaluate its performance using an intuitive interface.

---

### Instructions

#### Using the Notebook
1. **Load the Dataset**: Use the Breast Cancer Wisconsin dataset from `sklearn.datasets`.
2. **Preprocess the Data**: Handle missing values, normalize features, and split the data into training and testing sets.
3. **Train Models**: Implement and evaluate models like k-Nearest Neighbors (k-NN), Decision Trees, and Support Vector Machines (SVM).
4. **Evaluate Performance**: Analyze metrics such as accuracy, precision, recall, and F1-score.
5. **Explore Advanced Models**: Optionally, implement Random Forest and Gradient Boosting classifiers.

#### Using Obviously AI

##### Step 1: Upload the Dataset
- Download the Breast Cancer Wisconsin dataset from the UCI Machine Learning Repository or use the provided CSV file.
- In Obviously AI, go to the **Datasets** section and select **Upload Dataset**.
- Upload the CSV file.
- Verify that the data is correctly uploaded and review the available features.

##### Step 2: Configure the Model
- Click on **Create a New Model** and choose **Classification** as the model type.
- Select the target variable (`diagnosis`), which indicates whether the tumor is malignant (M) or benign (B).
- Ensure that all relevant features are included in the model training.

##### Step 3: Train the Model
- Click on **Predict** to let Obviously AI analyze the data and automatically choose the best classification model.
- Wait for the platform to train the model and display the results.

##### Step 4: Evaluate the Model
- Analyze the performance metrics provided, such as accuracy, precision, recall, and F1-score.
- Observe the feature importance graph and reflect on which attributes contribute the most to the prediction.

##### Step 5: Make Predictions
- Use the **Predict on New Data** option to upload a CSV file containing new data without labels.
- Download the results and analyze whether the model is reliable for real-world predictions.

---

**Note:** Students can choose to complete this exercise using Obviously AI, the provided notebook, or both methods to compare results and gain a deeper understanding of the process.


Main Goals:
- Preprocess the Data: Load, clean, and normalize the Breast Cancer Wisconsin dataset.
- Apply Machine Learning Algorithms: Train and evaluate k-NN, Decision Tree, and SVM models.
- [Bonus] Explore Advanced Models: Independently implement and assess Random Forest and Gradient Boosting classifiers.
