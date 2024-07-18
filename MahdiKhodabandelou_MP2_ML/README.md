# Mini Project 2: Neural Network Activation Functions and Perceptrons, Decision tree, Bayesian Classification

## Problem 1: Analyzing Activation Functions and Perceptrons

### Task 1: Impact of ReLU in a Two-Class Classification Problem
- **Description:**
  - Consider a two-class classification problem where the final layer of your network uses ReLU and sigmoid as the activation function.
  - **Objective:** What happens in this scenario?

### Task 2: Replacing ReLU with ELU
- **Description:**
  - Replace ReLU with ELU. Calculate its gradient and explain one advantage of ELU over ReLU.
  

### Task 3: Designing McCulloch-Pitts Neurons
- **Description:**
  - Design a simple perceptron using McCulloch-Pitts neurons to generate shapes within a defined area, as shown in the figure below.
  - ![image](https://github.com/user-attachments/assets/63c83801-ca11-405c-88e4-6663568a2086)

## Problem 2: Working with CWRU Bearing Dataset

### Task 1: Introduction to the CWRU Bearing Dataset
- **Description:**
  - Access the [CWRU Bearing Dataset](https://engineering.case.edu/bearingdatacenter) related to fault diagnosis, focusing on a specific fault type. Add two new conditions (`OR007@6_X` and `B007_X`) to the existing 12k sample dataset, analyzing both healthy and faulty conditions.
  
### Task 2: Feature Extraction
- **Description:**
  - Extract features from the dataset using statistical and time-domain methods. Create a matrix of features from the healthy and faulty data samples.
  - Discuss the significance of each feature and its impact on the classification results.

### Task 3: Training a Multi-Layer Perceptron (MLP)
- **Description:**
  - Train an MLP model using the extracted features. Select hyperparameters using cross-validation. Train the model and evaluate its performance using the `classification_report`.
  - Analyze the results based on accuracy and discuss the impact of different features on the model's performance.

### Task 4: Comparing ReLU with Another Activation Function
- **Description:**
  - Replace ReLU with another activation function and compare the results. Analyze the performance difference and discuss why the change affects the outcome.
  - Determine which activation function works best for this dataset and provide a detailed explanation of your findings.

### Task 5: Cross-Validation Techniques
- **Description:**
  - Explain the differences between Stratified K-Fold Cross-Validation and K-Fold Cross-Validation. 
  - Justify the choice of using one technique over the other for this specific problem. Implement the chosen technique and discuss the results.

## Problem 3: Classification with Ensemble Methods

### Task 1: Data Preparation
- **Description:**
  - Use a dataset related to either forest cover type classification or drug classification. Split the dataset into training and test sets, ensuring at least 15% of the data is used for testing. Explain the method used for splitting the data and its advantages.
  
### Task 2: Decision Tree Implementation
- **Description:**
  - Implement a decision tree classifier for the dataset. Write a program to construct and visualize the decision tree. Analyze the output manually and discuss the results.
  
### Task 3: Performance Evaluation
- **Description:**
  - Evaluate the performance of the decision tree classifier using at least one relevant metric. Report the results and analyze the impact of various hyperparameters on the model's performance. Discuss the advantages and disadvantages of the decision tree classifier.
  
### Task 4: Random Forest and AdaBoost
- **Description:**
  - Explain how ensemble methods like Random Forest and AdaBoost can improve classification results. Implement these methods using the dataset, and compare the results with the decision tree classifier. 
  - Use `sklearn.ensemble.RandomForestClassifier` and `sklearn.ensemble.AdaBoostClassifier` for implementation. Optimize the hyperparameters using techniques such as GridSearch.

### Task 5: Comparison and Analysis
- **Description:**
  - Compare the performance of the Random Forest and AdaBoost classifiers with the decision tree classifier. Analyze the results, discuss the impact of different hyperparameters, and determine which method works best for the dataset.

## Problem 4: Classification with Heart Disease Dataset

### Task 1: Data Preparation
- **Description:**
  - Use the Heart Disease dataset. Split the data into training and test sets, ensuring a proper split for cross-validation. Explain the preprocessing steps taken, such as normalization or handling missing values.
  
### Task 2: Bayesian Classification
- **Description:**
  - Implement a Gaussian Naive Bayes classifier using the dataset. Calculate the results in a confusion matrix and analyze the results. Use the `classification_report` from scikit-learn to explain the differences between Micro and Macro averages.
  
### Task 3: Random Sample Testing
- **Description:**
  - Randomly select five data points from the test set and compare the predicted results with the actual results. Discuss the accuracy and any discrepancies.

