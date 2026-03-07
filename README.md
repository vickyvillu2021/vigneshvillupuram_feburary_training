# Medical Insurance Cost Prediction

## conclusion:

This project focuses on predicting medical insurance charges using supervised machine learning techniques. The aim is to analyze how different personal attributes such as age, BMI, smoking status, and region influence insurance costs and to build models capable of estimating these charges accurately.

## Problem Statement

Medical insurance charges vary depending on several demographic and lifestyle factors. Predicting these costs can help insurance companies estimate risk and determine appropriate pricing. In this project, regression models are used to predict insurance charges based on the available dataset features.
 ## Dataset Information

The dataset used in this project contains records related to individuals and their corresponding medical insurance costs. Each record includes several personal and lifestyle attributes that may influence the total insurance charges.
The dataset consists of the following features:
* **Age** – Represents the age of the individual.
* **Sex** – Indicates the gender of the individual (male or female).
* **BMI (Body Mass Index)** – A numerical value calculated from a person’s height and weight that helps determine body fat levels.
* **Children** – Number of dependents covered by the insurance plan.
* **Smoker** – Indicates whether the individual is a smoker or non-smoker.
* **Region** – Specifies the residential area of the individual (such as northeast, southeast, southwest, or northwest).
* **Charges** – The total medical insurance cost billed to the individual.

Among these features, **charges** is the target variable that the machine learning models aim to predict, while the remaining attributes serve as input features.

## Data Preprocessing
Before training machine learning models, several preprocessing steps were performed to improve data quality and model performance.

**Steps Performed**

* Checked the dataset for missing values.
* Verified the correctness of data types.
* Removed duplicate records from the dataset.
* Detected potential outliers using visualization techniques.
* Converted categorical variables (sex, smoker, region) into numerical form using encoding.
* Applied feature scaling to normalize the dataset.
* Selected relevant features for prediction.
* Split the dataset into training and testing sets.
These preprocessing steps help ensure that the models learn meaningful patterns from the data.
## Machine Learning Models

Three regression algorithms were implemented and compared in this project.

**1. Linear Regression**
A simple regression model that estimates the relationship between independent variables and the target variable using a linear equation.
**2. Decision Tree Regressor**
A tree-based model that splits the dataset into multiple decision rules to predict the target value.
**3. Random Forest Regressor**
An ensemble learning technique that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

## Evaluation Metrics

The models were evaluated using the following regression metrics:

* **R² Score** – Measures how well the model explains the variance in the target variable.
* **Mean Squared Error (MSE)** – Measures the average squared difference between predicted and actual values.
* **Root Mean Squared Error (RMSE)** – Square root of MSE providing error in the same unit as the target variable.
* **Mean Absolute Error (MAE)** – Measures the average magnitude of prediction errors.

These metrics provide a clear comparison of model performance.

## Results and Observations

After training and testing the models, their performances were compared using the evaluation metrics. The comparison helps identify which algorithm provides better predictions for insurance charges.

Among the models tested, ensemble models such as Random Forest generally provide better accuracy due to their ability to capture complex relationships in the dataset.

## Conclusion

This project demonstrated the application of supervised machine learning techniques for predicting medical insurance costs. The workflow included data preprocessing, feature transformation, model training, and performance evaluation.
The results show that machine learning models can effectively predict insurance charges when appropriate preprocessing and evaluation techniques are applied. Ensemble models such as Random Forest tend to produce more reliable predictions compared to simpler regression methods.
Overall, this project highlights the importance of proper data preparation and model comparison when building predictive systems.
