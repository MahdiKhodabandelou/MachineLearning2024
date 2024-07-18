# Mini Project 3: Support Vector Machines (SVM) Analysis

## Problem 1: Exploring SVM with Iris Datasets

### Objective
The goal of this problem is to explore the SVM algorithm on Iris datasets. Follow the steps below and include your findings in the report.

### Task 1: Data Loading and Initial Analysis
- **Description:**
  - Load the datasets and analyze their structure, including the number of samples, features, and classes.
  - Perform an initial visualization of the datasets (using techniques like t-SNE) to understand their structure.
  - **Objective:** Understand the basic characteristics of the datasets and prepare for further analysis.

### Task 2: Applying SVM 
- **Description:**
  - Apply the SVM with linear kernel to dataset.
  - Visualize the decision boundaries.

### Task 3: Comparison with Other Kernels
- **Description:**
  - Compare the results of SVM with polynomyal kernel and different degrees using scikit-learn.
  - Visualize and analyze the results, and create a summary GIF comparing the performance of degrees.

### Task 4: Implementing SVM from Scratch
- **Description:**
  - Implement the SVM algorithm from scratch without using scikit-learn or any other library's built-in SVM functionality.
  - Compare the results of your implementation with scikit-learn's SVM. Explain any differences and difficulties encountered during the implementation.
  - **Objective:** Understand the inner workings of the SVM algorithm by implementing it manually.

## Problem 2: Studying GenSVM: A Generalized Multiclass Support Vector Machine

### Objective
The goal of this problem is to study the GenSVM algorithm and compare its performance with traditional SVM on the IRIS dataset.

### Task 1: Studying the GenSVM Paper
- **Description:**
  - Read and study the paper "GenSVM: A Generalized Multiclass Support Vector Machine".
  - Summarize the problem statement, proposed method, and overall contributions of the paper.
  - **Objective:** Understand the key ideas and innovations presented in the GenSVM paper.

### Task 2: Implementing GenSVM
- **Description:**
  - Implement the GenSVM algorithm based on the descriptions and methods provided in the paper.
  - Compare the results of the GenSVM implementation with those obtained using traditional SVM.
  - Use the IRIS dataset for implementation and testing.
  - **Objective:** Evaluate the performance and effectiveness of GenSVM compared to traditional SVM.

## Problem 3: Credit Card Fraud Detection Using Autoencoder Neural Network

### Objective
The goal of this problem is to implement and analyze the autoencoder neural network for credit card fraud detection based on the specified paper.

### Task 1: Understanding the Challenges
- **Description:**
  - Read the paper "Credit Card Fraud Detection Using Autoencoder Neural Network".
  - Explain the challenges of fraud detection models and the methods used to address these challenges in the paper.
  - **Objective:** Summarize the problem and methods used in the paper.

### Task 2: Model Architecture
- **Description:**
  - Describe the architecture of the autoencoder neural network used in the paper.
  - **Objective:** Provide a concise description of the model architecture.

### Task 3: Implementing the Model
- **Description:**
  - Implement the autoencoder neural network based on the paper. Use a dataset provided in the paper or a similar one.
  - Train the model and prevent overfitting by using techniques like early stopping.
  - **Objective:** Train an effective autoencoder model for fraud detection.

### Task 4: Evaluation Metrics
- **Description:**
  - Evaluate the model using Recall, Precision, Accuracy, and F1-score on the test data.
  - Discuss why certain metrics like Accuracy might not be the best indicator for this problem.
  - **Objective:** Provide a thorough evaluation of the model's performance.

### Task 5: Oversampling Techniques
- **Description:**
  - Test different oversampling techniques to address class imbalance and improve the model's performance.
  - Plot the Recall and Accuracy of the model with and without oversampling.
  - **Objective:** Analyze the impact of oversampling on model performance.

### Task 6: Comparison
- **Description:**
  - Compare the model's performance with and without oversampling using the same evaluation metrics.
  - **Objective:** Determine the effectiveness of oversampling in fraud detection.

### Task 7: Final Model and Report
- **Description:**
  - Present the final model and discuss the results from previous tasks.
  - **Objective:** Provide a comprehensive report on the findings and final performance of the model.
