# Social Media Impact on Life - Machine Learning

## Project Overview

This project uses Machine Learning classification algorithms to predict the overall impact of social media usage on students' lives. The target variable is `Overall_Impact`, which contains three categories: Beneficial, Neutral, and Negative.

## Dataset

The dataset contains information about students' social media usage, lifestyle, mental health, and academic performance.

Features include:
- Age
- Gender
- Academic Level
- Primary Platform
- Daily Usage Hours
- Weekend Extra Hours
- Device Type
- Sleep Duration
- Sleep Quality Score
- Late Night Usage
- Social Comparison Frequency
- Perceived Stress Score
- Mental Health Index
- Academic Performance GPA

Target Variable:
`Overall_Impact`

Classes:
- Beneficial
- Neutral
- Negative

## Machine Learning Models

The following classification algorithms were implemented and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Gaussian Naive Bayes

## Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset using Pandas.
- Checked the dataset shape, data types, and missing values.
- Filled missing numerical values using the mean.
- Removed `Student_ID` because it is an identifier.
- Converted categorical variables into numerical variables using one-hot encoding.
- Converted `Late_Night_Usage` into numerical values.
- Separated features (X) and target (y).
- Split the dataset into training and testing sets.
- Used stratified sampling to maintain class distribution.
- Applied StandardScaler where required.

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score

F1 Score was also considered when comparing the models because the target classes have different numbers of samples.

## Visualizations

The project includes:

- Accuracy comparison of all machine learning models.
- F1 Score comparison of all machine learning models.
- Confusion matrix for the selected model.
- Classification report for the selected model.

## Model Selection

All four models are compared using their test-set F1 Scores. The model with the highest F1 Score is automatically selected as the best-performing model for this dataset.

The selected model is then used to generate the classification report and confusion matrix.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

Social-Media-Impact-ML/
├── Social_media_impact_on_life.csv
├── social_media_impact.ipynb
├── README.md
└── requirements.txt

## Requirements

numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter

## How to Run

1. Clone the repository:

git clone YOUR_GITHUB_REPOSITORY_LINK

2. Open the project folder in VS Code or Jupyter Notebook.

3. Install the required libraries:

pip install -r requirements.txt

4. Open `social_media_impact.ipynb` and run the cells sequentially.

## Objective

The objective of this project is to demonstrate how supervised machine learning can be used to classify the overall impact of social media usage on students based on behavioral, lifestyle, mental health, and academic-related features.

## Author

Nitesh Kumar Jaiswal

Computer Science Engineering Student
