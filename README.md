### GenAarogya
## 🧬 Overview:
GenAarogya is a machine learning project aimed at predicting rare genetic disorders using clinical and genetic data. Leveraging advanced algorithms, it seeks to assist healthcare professionals in early diagnosis and personalized treatment planning.

## 🛠 Features
-Data Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.
-Exploratory Data Analysis: Visualizations and statistical analysis to understand data distributions and relationships.
-Modeling: Implementation of machine learning models such as Random Forest, Support Vector Machines, and Neural Networks.
-Evaluation: Assessment using metrics like accuracy, precision, recall, and F1-score.

## 🤖 Machine Learning Models
A variety of models were explored and compared using metrics like Accuracy, Precision, Recall, and F1-Score:

| Model                     | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| Logistic Regression       | A simple linear model used as a baseline classifier.                        |
| Decision Tree Classifier  | A non-linear, interpretable model that works well on tabular data.          |
| Random Forest Classifier  | An ensemble method that combines multiple trees to reduce overfitting.      |
| K-Nearest Neighbors (KNN) | A distance-based classifier sensitive to feature scaling.                   |
| Support Vector Machines   | High-performance classifier with kernel support for complex classification.|
| Gradient Boosting         | Builds trees sequentially to minimize prediction error.                     |
| XGBoost (if implemented)  | Optimized gradient boosting with enhanced performance and speed.            |

Each model was tuned and evaluated using cross-validation and confusion matrices to assess performance on the target column: `Combined_disorder`.


##  Feature Scaling
To ensure uniformity in feature magnitudes, we used various scalers such as:
StandardScaler – Standardizes features by removing the mean and scaling to unit variance.
MinMaxScaler – Scales each feature to a given range (default 0 to 1).
RobustScaler – Robust to outliers, uses median and interquartile range.
Scaling improves convergence and model performance, particularly for algorithms sensitive to feature distributions (like KNN, SVM, Logistic Regression).

## 📄 License
This project is licensed under the MIT License — feel free to use, modify, and contribute!


