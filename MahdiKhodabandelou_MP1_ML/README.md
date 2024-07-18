# Mini Project 1: Classification with Linear Models,  LS and RLS

## Problem 1: Training and Evaluating a Classification Model

### Task 1: Visualizing the Classification Process
- **Description:** 
  - Train a linear classification model and visualize the decision boundary. Display this boundary on a scatter plot with various components.
 

### Task 2: Generating and Visualizing a Dataset
- **Description:**
  - Use `sklearn.datasets` to generate a dataset with 1000 samples, 4 classes, and 2 features. Display this dataset in a scatter plot.


### Task 3: Using Logistic Regression for Classification
- **Description:**
  - Train a logistic regression model (`sklearn.linear_model`) with at least two classes. Use cross-validation to determine the best hyperparameters.


### Task 4: Visualizing Decision Boundaries
- **Description:**
  - Show the decision boundaries of the trained model with sample points in one plot. Include different shapes and colors for classes.


### Task 5: Repeating with New Data
- **Description:**
  - Use the `drawdata` tool to create new datasets and repeat the classification and visualization process.


## Problem 2: Working with CWRU Bearing Dataset

### Task 1: Introduction to the CWRU Bearing Dataset
- **Description:**
  - Access the [CWRU Bearing Dataset](https://engineering.case.edu/bearingdatacenter) related to fault diagnosis. Provide an overview of the dataset, its objectives, and different states.


### Task 2: Forming the Dataset
- **Description:**
  - Separate data into classes (M classes with N samples each) and form a matrix of 100 samples and 200 data points for each class.
  - Extract 8 features from the data using the formulas provided in Table 1.

### Task 3: Extracting Features
- **Description:**
  - Extract features from the dataset using the methods listed in Table 1. Create a dataset consisting of these features.


### Task 4: Describing the Normalization Process
- **Description:**
  - Explain the normalization process used for the features. Discuss its importance and impact on the results.


### Task 5: Data Visualization
- **Description:**
  - Visualize the dataset features. Use various plots to illustrate the distribution and relationships between features.


### Task 6: Evaluating the Model
- **Description:**
  - Train and evaluate a classification model using logistic regression without using libraries. Calculate and plot the learning curve and confusion matrix. Analyze the results to determine the model’s performance.


### Task 7: Training and Evaluating with `sklearn`
- **Description:**
  - Train and evaluate a linear classification model using `sklearn.linear_model`. Compare the results with the manually implemented model. Display the learning curve and confusion matrix.


### Task 8: Investigating with Orange
- **Description:**
  - Investigate the Orange data mining software. Recreate one of the tasks using Orange and compare the results. Provide a visual and video explanation of the process and findings.


## Problem 3: Weather Data Analysis

### Task 1: Introduction to Weather Dataset
- **Description:**
  - Access the [Weather in Szeged 2006-2016](https://www.kaggle.com/datasets) dataset. The goal is to find the relationship between Temperature and Humidity, and Apparent Temperature and Humidity.


### Task 2: Plotting and Analyzing Features
- **Description:**
  - Plot the correlation matrix and histogram for the features. Analyze the plots to identify any patterns or anomalies.


### Task 3: Implementing LS and RLS
- **Description:**
  - Implement Least Squares (LS) and Recursive Least Squares (RLS) to fit the data. Adjust hyperparameters as necessary. Plot the results and compare the models.


### Task 4: Investigating Weighted Least Squares
- **Description:**
  - Explain and implement Weighted Least Squares (WLS). Apply it to the dataset and compare the results with LS and RLS.


### Task 5: QR-Decomposition-Based RLS
- **Description:**
  - Investigate and implement QR-Decomposition-Based RLS. Explain the algorithm and apply it to the dataset.

