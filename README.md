## End-to-End SMS Spam Classifier

### Overview
This project aims to develop a robust SMS spam classifier using a dataset from Kaggle. The primary goal is to accurately distinguish between spam and non-spam messages, ensuring effective filtering and enhancing user experience. The project involves various stages, including data cleaning, exploratory data analysis (EDA), data preprocessing, model building, evaluation, and deployment using Streamlit.

### Dataset
The dataset used in this project is sourced from Kaggle and consists of labeled SMS messages categorized as either spam or non-spam. The dataset is divided into training and testing sets to facilitate model evaluation and validation. [Link to Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

### Project Steps

#### Data Cleaning
- Removal of duplicates and irrelevant characters
- Standardization of text data
- Handling of missing values (if any)

#### Exploratory Data Analysis (EDA)
- Visualization of data distribution
- Analysis of word frequency in spam and non-spam messages
- Identification of common patterns and trends

#### Data Preprocessing
- Tokenization and lemmatization of text
- Conversion of text to numerical format using techniques like TF-IDF
- Splitting the data into training and testing sets

#### Model Building and Comparison
- Development of multiple machine learning models, including:
  - XGBoost
  - Gradient Boosting
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - Naive Bayes
  - Support Vector Classifier (SVC)
  - Logistic Regression
  - And more
- Comparison of model performance based on precision, recall, F1-score, and accuracy

#### Model Selection
- Selection of the best-performing model based on precision
- In this case, Naive Bayes provided the highest precision and was chosen for deployment

#### Interface Development
- Creation of a user-friendly interface using Streamlit
- Implementation of features allowing users to input SMS messages and receive real-time classification results
- Visualization of model performance metrics
