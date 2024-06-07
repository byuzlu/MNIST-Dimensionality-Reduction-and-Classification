# README

## Project Overview

This project involves two primary tasks: applying Principal Component Analysis (PCA) to the MNIST dataset to understand the variance captured by principal components, and developing a Multinomial Logistic Regression Classifier for digit classification. The MNIST dataset contains 70,000 grayscale images of handwritten digits, split into 60,000 training and 10,000 test images, each with a 28x28 pixel resolution.

## Dataset Description

- **MNIST Dataset**:
  - **Training Set**: 60,000 images
  - **Test Set**: 10,000 images
- **Image Resolution**: 28x28 pixels
- **Labels**: Digits from 0 to 9

## Task 1: PCA Analysis

### Steps

1. **Load Dataset**: Utilize provided scripts to read the MNIST dataset.
2. **Apply PCA**: Perform PCA to extract principal components from the dataset.
3. **Variance Explained**:
   - Calculate and report the proportion of variance explained (PVE) by the first 10 principal components.
   - Determine the number of principal components required to explain 70% of the total variance.
4. **Projection and Visualization**:
   - Project the first 100 images onto the first 2 principal components.
   - Visualize the projected data points in a 2D scatter plot, coloring them based on their digit labels.
   - Label the plot axes according to the principal components.
5. **Analysis**: Discuss how the data points are distributed according to their labels in the 2D space defined by the first 2 principal components.

## Task 2: Multinomial Logistic Regression

### Steps

1. **Split Dataset**:
   - Create a validation set by separating the first 10,000 images from the training set.
   - Resulting in 50,000 training, 10,000 validation, and 10,000 test images.
2. **One-Hot Encoding**: Convert digit labels to one-hot encoded vectors.
3. **Initialize Model**: Set up a weight matrix with bias terms for the Multinomial Logistic Regression Classifier.
4. **Train Model**: Fit the model on the training set.
5. **Evaluate Model**:
   - Validate the model on the validation set.
   - Test the model on the test set and report the classification accuracy.
6. **Performance Metrics**: Discuss the accuracy and performance of the logistic regression model.

## Implementation

### Prerequisites

- Python 3.10
- Required Libraries: pandas, numpy, scikit-learn, matplotlib

### Instructions

1. **Load Dataset**: Use the provided script to load the MNIST dataset.
2. **PCA Analysis**:
   - Apply PCA to the dataset and calculate the proportion of variance explained by the first 10 principal components.
   - Determine the number of principal components needed to explain 70% of the data variance.
   - Project the first 100 images onto the first 2 principal components and visualize the results.
3. **Multinomial Logistic Regression**:
   - Split the dataset into training, validation, and test sets.
   - Encode the labels and initialize the logistic regression model.
   - Train the model on the training set and evaluate its performance on the validation and test sets.
   - Report and discuss the accuracy and performance metrics.

## Conclusion

This project demonstrates the application of PCA for dimensionality reduction and visualization of the MNIST dataset, as well as the implementation of a Multinomial Logistic Regression Classifier for digit classification. The analysis provides insights into the variance captured by principal components and the effectiveness of logistic regression for classifying handwritten digits.

## Contributions and Support

Contributions and feedback are welcome to enhance the functionality and usability of the methods explored in this project. For any questions or assistance, please reach out to baha.yuzlu@gmail.com. Thank you for your interest and support!
