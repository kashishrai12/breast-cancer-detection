# Breast Cancer Detection

This project utilizes a Naive Bayes classifier to detect breast cancer based on the characteristics of cell nuclei present in breast tissue. The dataset used is the Breast Cancer Wisconsin dataset, which contains various features extracted from digitized images of breast tissue samples.

## Project Overview

The objective of this project is to build a machine learning model that can accurately classify whether a tumor is benign or malignant based on input features.

### Key Steps:

1. **Data Loading and Preprocessing**:
    - Load the dataset and inspect its basic properties.
    - Handle any missing values and prepare the data for analysis.

2. **Exploratory Data Analysis (EDA)**:
    - Perform initial exploration to understand the distribution and relationships between features.

3. **Model Training**:
    - Train a Naive Bayes model using `GaussianNB` from `scikit-learn`.
    - Split the dataset into training and testing subsets.

4. **Model Evaluation**:
    - Evaluate the model's performance using accuracy as the primary metric.
    - Use the trained model to make predictions on the test set.

## Dependencies

The following Python libraries are required to run the notebook:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib` (if used for plotting)

You can install these dependencies using pip:

```bash
pip install pandas numpy scikit-learn matplotlib
