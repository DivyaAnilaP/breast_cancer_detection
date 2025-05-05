🧠 Breast Cancer Prediction Using Logistic Regression
This project is a machine learning model built using Logistic Regression to classify whether a tumor is Malignant (cancerous) or Benign (non-cancerous) based on real-world Breast Cancer Wisconsin Diagnostic Dataset from sklearn.datasets.

📌 Problem Statement
Breast cancer is one of the most common cancers worldwide. Early diagnosis and classification can drastically improve treatment outcomes. This project leverages a supervised learning algorithm to predict the nature of a tumor based on a set of diagnostic features.

📊 Dataset
Source: sklearn.datasets.load_breast_cancer()

Features: 30 numerical features (e.g., mean radius, mean texture, mean perimeter)

Target: Binary classification

0 → Malignant

1 → Benign

Total records: 569

🛠️ Technologies Used
Python

NumPy

Pandas

scikit-learn (sklearn)

🔍 Workflow Summary
Load and explore the dataset

Understand feature names, shapes, and check for missing values.

Use .info(), .describe(), and .value_counts() for insights.

Preprocess the data

Convert the dataset into a Pandas DataFrame.

Add the target column to the DataFrame.

Split the data into features (X) and target labels (Y).

Perform train-test split (80% train, 20% test).

Model training

Train a Logistic Regression model using the training data.

Model Evaluation

Evaluate performance using accuracy score on both training and test sets.

Make Predictions

Use a new sample (given as input_data) to predict whether the tumor is malignant or benign.

📈 Results
Training Accuracy: ~92%

Test Accuracy: ~94%

The model shows strong generalization performance.

