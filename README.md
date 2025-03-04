Overview

This project focuses on predicting whether a customer will purchase an insurance policy based on various factors such as age, driving history, 
vehicle attributes, and other demographic information. The dataset used for this project contains information about potential insurance buyers, 
and the goal is to build a predictive model that helps insurance companies optimize their marketing efforts.

Dataset:

The dataset contains features such as:

Age: Customer's age

Gender: Male/Female

Vehicle Age: Age of the vehicle

Vehicle Damage: Whether the vehicle has had previous damage

Annual Income: Amount of Anuual Income for each customer

Policy Sales Channel: Marketing channel through which the policy was sold

Previously Insured: Whether the customer was insured previously

Vehicle Type: Represent the type of car for each customer ranging from Normal Car to Luxury SUV

Location_Type: show each customer locate in Urban area, Suburban, Rural


Exploratory Data Analysis (EDA)

The dataset underwent detailed EDA to:

Identify missing values and handle them appropriately

Perform statistical analysis of key variables

Visualize relationships between features and the target variable using histograms, bar charts, and correlation heatmaps

Analyze class imbalance in the target variable

Data Preprocessing

Preprocessing steps include:

Handling missing values

Encoding categorical variables

Normalizing numerical features

Splitting data into training and testing sets


Model Implementation

Two machine learning models were implemented:

Logistic Regression: A baseline model for binary classification.

Decision Tree Classifier: A tree-based model that captures complex relationships between variables.

Evaluation Metrics

The models were evaluated based on:

Accuracy: Measures the overall correctness of the predictions.

Precision, Recall, and F1-Score: Important metrics for imbalanced datasets.


Results and Insights

The decision tree model outperformed logistic regression in capturing complex relationships but was prone to overfitting.

Feature importance analysis showed that Vehicle Age, Previously Insured, and Vehicle Damage were the most influential features.

Data balancing techniques may be required to further improve model performance.

Future Improvements

Implement ensemble models such as Random Forest and Gradient Boosting.

Fine-tune hyperparameters for better model performance.

Experiment with feature selection and engineering to improve predictive power.

