# Rock-Mine-prediction-for-submarines
Using Random Forest Classifier

# About the project
This project focuses on building a machine learning model to classify sonar signals into two categories: Rock (R) or Mine (M). The goal is to predict whether a given sonar signal reflects off a rock or a mine.

Why Random Forest Classifier?
Random Forest is an ensemble learning method that combines multiple decision trees to improve the model's accuracy and robustness.
Here are some reasons why Random Forest is a better choice for this problem:

1. Handles Overfitting: Random Forest reduces the risk of overfitting by averaging the results of multiple decision trees, which helps in generalizing the model better.

2. Robustness to Noise: Random Forest is less sensitive to noise in the data compared to other algorithms like decision trees, making it more reliable for real-world datasets.

3. Scalability: Random Forest can handle large datasets with higher dimensionality, making it suitable for datasets with many features, like the sonar dataset used in this project.

4. Non-linearity: Random Forest can capture non-linear relationships between features and the target variable, which is often the case in real-world datasets.

5. Versatility: It can be used for both classification and regression tasks, making it a versatile choice for various machine learning problems.

# About the dataset
The dataset contains 208 rows of data, each representing a sonar signal reading. Each row consists of 60 numerical features (attributes) and a label at the end indicating the class of the signal.

Number of Features: 60
Feature Values: 
Each feature is a floating-point number, likely representing the energy within a particular frequency band of the sonar signal. 
The values are normalized, typically ranging between 0 and 1.

Label Values:
The last column in each row is a label indicating the class of the sonar signal. 
The labels are:
R: Represents "Rock" (likely indicating that the sonar signal was reflected off a rock).
M: Represents "Metal" (likely indicating that the sonar signal was reflected off a metal object, such as a mine).

Structure:
Rows: Each row corresponds to a single sonar signal reading.
Columns: The first 60 columns are the features, and the last column is the label.

Use case
Classification: The dataset is commonly used for binary classification tasks, where the goal is to predict whether a sonar signal is reflected off a rock or a metal object.

# dataset source : UCI Machine Learning Repository
https://archive.ics.uci.edu/dataset/151/connectionist+bench+sonar+mines+vs+rocks
