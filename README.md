# Predicting Medical Appointment No-Shows

This project analyzes medical appointment data to predict whether a patient will show up for their appointment or not. The dataset includes various features such as patient demographics, appointment details, and health indicators.

## 📁 Dataset

The dataset is from the [Kaggle No-show Medical Appointments Dataset](https://www.kaggle.com/datasets/joniarroba/noshowappointments). It contains information from over 100,000 medical appointments in Brazil.

## 🔍 Problem Statement

The goal is to build a machine learning model that can predict whether a patient will miss their appointment based on the available data. This can help optimize scheduling and reduce no-show rates.

## 🔄 Workflow

### 1. Data Exploration and Cleaning
- Load the dataset
- Check for null values and incorrect data types
- Rename columns for consistency
- Remove or correct invalid records (e.g. negative ages)

### 2. Exploratory Data Analysis (EDA)
- Univariate analysis of key variables (age, scholarship, SMS_received, etc.)
- Bivariate analysis to understand relationships with the target variable (`No-show`)
- Visualizations to identify trends and correlations

### 3. Feature Engineering
- Convert date columns to datetime
- Create new features (e.g. waiting time)
- Encode categorical variables
- Normalize/scale features if necessary

### 4. Model Building
- Split data into train and test sets
- Train models including:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - K-Nearest Neighbors
- Evaluate models using accuracy, precision, recall, F1-score

### 5. Model Evaluation and Selection
- Compare model performance
- Analyze confusion matrix
- Select the best-performing model based on metrics

### 6. Conclusion
- Summarize findings from the EDA and model performance
- Discuss limitations and possible future improvements

## 🛠 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📌 Results
- Random Forest performed best with the highest accuracy
- Key features affecting no-shows: SMS_received, scholarship status, waiting time, age

## 📚 References
- [Original Kaggle Dataset](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
