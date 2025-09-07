# -Wine-Quality-Prediction
The focus is on predicting the quality of wine based on its chemical characteristics, offering a real-world application of machine learning in the context of viticulture. The dataset encompasses diverse chemical attributes, including density and acidity, which serve as the features for three distinct classifier models.

This project focuses on predicting the quality of wine based on its chemical characteristics, demonstrating a real-world application of machine learning in the field of viticulture.

The dataset includes several chemical features such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, density, pH, sulphates, alcohol, and more, which are used to classify wines into quality categories.

📌 **Project Overview**

Goal: Predict wine quality using chemical composition data.

Dataset: Wine Quality Dataset (UCI Machine Learning Repository).

Features: Chemical properties of wine (e.g., density, acidity).

Target: Wine quality score (integer values).

Models Implemented:

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

🗂️ **Dataset Description**

Each row in the dataset represents a wine sample with the following attributes:

Fixed acidity

Volatile acidity

Citric acid

Residual sugar

Chlorides

Free sulfur dioxide

Total sulfur dioxide

Density

pH

Sulphates

Alcohol

Quality (target variable)

⚙️ **Workflow**

Data Preprocessing

Handle missing values (if any).

Feature scaling/normalization.

Train-test split.

Exploratory Data Analysis (EDA)

Distribution of quality scores.

Correlation between chemical attributes and wine quality.

Visualization of feature importance.

Model Training & Evaluation

Logistic Regression

Random Forest Classifier

SVM

Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix

Model Comparison

Compare performance of all three models.

Select best-performing classifier.

📊 **Results**

Logistic Regression: Baseline performance.

Random Forest: High accuracy and interpretability through feature importance.

SVM: Good performance with optimized kernel.
