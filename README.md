# Rock-Mine-prediction-for-submarines
Using Random Forest Classifier


# The dataset contains 208 rows of data, each representing a sonar signal reading. Each row consists of 60 numerical features (attributes) and a label at the end indicating the class of the signal.

# Number of Features: 60

# Feature Values: 
Each feature is a floating-point number, likely representing the energy within a particular frequency band of the sonar signal. 
The values are normalized, typically ranging between 0 and 1.

# Label Values:
The last column in each row is a label indicating the class of the sonar signal. 
The labels are:
R: Represents "Rock" (likely indicating that the sonar signal was reflected off a rock).
M: Represents "Metal" (likely indicating that the sonar signal was reflected off a metal object, such as a mine).

# Structure:
Rows: Each row corresponds to a single sonar signal reading.
Columns: The first 60 columns are the features, and the last column is the label.

# Use case
Classification: The dataset is commonly used for binary classification tasks, where the goal is to predict whether a sonar signal is reflected off a rock or a metal object.

# dataset source : UCI Machine Learning Repository
https://archive.ics.uci.edu/dataset/151/connectionist+bench+sonar+mines+vs+rocks
