# DiabetesClassification

This project aims to predict diabetes based on data obtained from a questionnaire available on Kaggle.com.

## Project Flow
The processes involved in this project include:
- Data loading
- EDA (Exploratory Data Analysis)
- Feature Engineering
  - Feature selection
  - Feature creation
  - Feature transformation
  - Column transformer
- Model definition using:
  - KNN
  - SVM
  - Decision Tree
  - Random Forest
  - Gradient Boost
- Model training
- Model evaluation

## The conclusions from this project are:

- EDA Results: The majority of the population falls into the Healthy Weight and Overweight categories. The Healthy Weight category tends to have better GenHlth (General Health), MentHlth (Mental Health), and PhysHlth (Physical Health) scores compared to other categories, especially Obesity Class 3, which has the lowest health scores. Additionally, as age increases, individuals in the Healthy Weight category tend to maintain better general health, while those in the Obesity Class 3 category tend to experience a decline in general health.
- Model Evaluation Results: The KNN model performed better than the other models, and the baseline KNN model outperformed the KNN with hyperparameters.
- Data Imbalance: There is an imbalance in the data, leading to an F1 Score below 80. This is due to a higher number of non-diabetic cases compared to prediabetic or diabetic cases, causing the predictions to skew towards non-diabetic outcomes.
