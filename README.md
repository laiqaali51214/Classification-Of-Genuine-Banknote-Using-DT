# Classification of Genuine Banknotes Using Decision Trees

## Overview
This project aims to classify genuine and counterfeit banknotes using a Decision Tree (DT) model. The dataset contains extracted features from banknote images obtained through wavelet transform. The objective is to train a classifier that can distinguish between authentic and fraudulent banknotes effectively.

## Dataset
The dataset includes numerical features derived from wavelet transforms of banknote images. Each sample in the dataset represents a banknote with the following attributes:
- **Variance of Wavelet Transformed Image**
- **Skewness of Wavelet Transformed Image**
- **Kurtosis of Wavelet Transformed Image**
- **Entropy of Image**
- **Class Label (0: Fake, 1: Genuine)**

## Implementation Details
The project is implemented in a Jupyter Notebook using Python. The key steps involved are:
1. **Data Preprocessing:**
   - Loading the dataset
   - Handling missing values (if any)
   - Splitting the dataset into training and testing sets
2. **Model Training:**
   - Initializing and training a Decision Tree classifier
   - Tuning hyperparameters to improve performance
3. **Model Evaluation:**
   - Measuring accuracy, precision, recall, and F1-score
   - Visualizing the Decision Tree
   - Generating a confusion matrix

## Technologies Used
- Python
- Jupyter Notebook
- Scikit-learn (for machine learning model)
- Pandas & NumPy (for data manipulation)
- Matplotlib & Seaborn (for visualization)

## Results
The trained Decision Tree model achieves high accuracy in classifying genuine and fake banknotes. The classification performance is evaluated using:
- Accuracy Score
- Precision, Recall, and F1-score
- Confusion Matrix Visualization

## Future Enhancements
- Implementing other machine learning models like Random Forest and SVM for comparison.
- Using feature engineering techniques to improve accuracy.
- Deploying the model as a web application.



