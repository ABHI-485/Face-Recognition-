# Face-Recognition-

# Facial Recognition Using PCA and SVM

This project leverages Principal Component Analysis (PCA) and Support Vector Machines (SVM) to perform facial recognition. It uses the Labeled Faces in the Wild (LFW) dataset to classify faces and predict their labels.

## Features
- **Data Preprocessing**: Uses PCA for dimensionality reduction and whitening.
- **Classification**: SVM with grid search optimization.
- **Visualization**: Provides a visual summary of predictions and errors, alongside a confusion matrix.

## Dataset
The LFW dataset contains images of individuals with varying numbers of samples per person. We work with a subset containing individuals with at least 60 images.

### Summary of Dataset
- Classes: 7 (e.g., Ariel Sharon, Colin Powell, etc.)
- Number of images: 1277
- Image dimensions: 62x47 pixels (grayscale)

## Implementation
### Modules Used
- **Scikit-learn**: For PCA, SVM, grid search, and model evaluation.
- **Matplotlib & Seaborn**: For visualization.
- **NumPy**: For data manipulation.

### Steps
1. Load the LFW dataset.
2. Preprocess data using PCA for dimensionality reduction.
3. Build a pipeline combining PCA and SVM.
4. Split dataset into training and testing sets.
5. Optimize SVM hyperparameters using GridSearchCV.
6. Train the best model on the training set.
7. Evaluate the model using precision, recall, and F1 scores.
8. Visualize predictions and the confusion matrix.

### Model Performance
- Accuracy: ~84%
- Detailed classification report and confusion matrix are included in the script.

## Visualization
- **Predicted Labels**: Correctly predicted labels are shown in black; incorrect predictions are highlighted in red.
- **Confusion Matrix**: Visualizes true vs. predicted labels.


   
