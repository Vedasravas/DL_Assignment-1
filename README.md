This notebook contains the implementation of Linear Regression and Neural Network models for a Cancer-related dataset. The code was developed and executed in Google Colab, an online IDE similar to Jupyter Notebook.

**Overview**

The notebook includes:

Code to load and preprocess the dataset.

Implementation of Linear Regression and various Deep Neural Network (DNN) models with different architectures and learning rates.

A test_model function to load a trained model and test it on the test dataset for prediction.

Plots generated using matplotlib to visualize the results for different learning rates ranging from 0.1 to 0.0001.
Instructions to Run the Code

The project starts with the general import statements.

You will need to upload the CSV data file, as Google Colab does not save files.

Once the data is uploaded, you can execute the notebook code blocks in sequence. Successfully executed blocks will show a green check on the left-hand side.

To run all code cells at once, use the "Run all" option from the Runtime menu at the top of the Google Colab interface.
Code Walkthrough.

**Reading the Dataset:**

Code for reading the CSV file is implemented. It loads the Cancer-related dataset into a DataFrame.
Data Preprocessing:

The dataset is split into training, validation, and test sets with the comment:
“Separating the dataset into training set, validation and testing set”.
Feature Scaling:

Feature scaling is applied, indicated by the comment:
“Feature scaling”.

**Linear Regression Model:**

The code for a linear regression model is implemented with the comment:
“Linear Search”.

Deep Neural Network Models (DNN): The following DNN models with different architectures and learning rates are implemented:

DNN-16 Architecture:

**Learning Rate: 0.001, with the comment:**

“New code for dnn 16 Learning rate .001”.
Learning Rate: 0.01, with the comment:
“DNN-16 model learning rate .01”.
Learning Rate: 0.1, with the comment:
“Implementing DNN-16 for learning rate .1”.
Learning Rate: 0.0001, with the comment:
“Implementing DNN-16 for LR :0001”.
DNN-30-8 Architecture:

**Learning Rate: 0.1, with the comment:**

“Implementing the DNN-model 30-8 with learning rate .1”.
Learning Rate: 0.01, with the comment:
“Implementing code 30-8 dnn model with Lr rate .01”.
Learning Rate: 0.001, with the comment:
“Implementing dnn 30-8 model with .001 learning rate”.
Learning Rate: 0.0001, with the comment:
“Implement 30-8 model with .0001 learning rate”.
DNN-30-8-16 Architecture:

**Learning Rate: 0.1, with the comment:**

“Implement 30-8-16 model with .1 learning rate”.
Learning Rate: 0.01, with the comment:
“Implement 30-8-16 dnn models in learning rate .01”.
Learning Rate: 0.001, with the comment:
“Implementing 30-8-16 dnn model for .001 learning rate”.
Learning Rate: 0.0001, with the comment:
“Implement 30-16-8 dnn model with .0001 learning rate”.
DNN-30-16-8-4 Architecture:

**Learning Rate: 0.1, with the comment:**

“Implement 30-16-8-4 dnn model with learning rate .1”.
Learning Rate: 0.01, with the comment:
“Implement 30-16-8-4 dnn model with .01 learning rate”.
Learning Rate: 0.001, with the comment:
“Implement the 30-16-8-4 dnn model for learning rate .001”.
Learning Rate: 0.0001, with the comment:
“Implement code for 30-16-8-4 dnn model with .0001 learning rate”.

**Model Testing:**

The test_model function is provided to load a trained model and test it on the test dataset to predict outcomes.
Results Visualization:

Plots are generated at the end of the notebook using matplotlib, displaying the results for the various learning rates (0.1, 0.01, 0.001, 0.0001).
