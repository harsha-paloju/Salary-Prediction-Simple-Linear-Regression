# Salary Prediction using Simple Linear Regression

## Project Overview

This project uses Simple Linear Regression to predict employee salary based on Years of Experience. It is a beginner-friendly Machine Learning project that demonstrates how linear regression works in real-world salary prediction problems.

The model is trained using historical salary data and helps estimate salary values for new experience inputs.

---

## Problem Statement

Companies often want to estimate employee salaries based on experience levels. This project helps solve that problem using Machine Learning by building a prediction model with Simple Linear Regression.

---

## Dataset Information

The dataset contains two columns:

- YearsExperience → Number of years of work experience
- Salary → Salary of the employee

This is a supervised learning regression problem where salary is the target variable.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Project Workflow

### 1. Import Libraries

Imported all required libraries such as pandas, numpy, matplotlib, and sklearn.

### 2. Load Dataset

Loaded the salary dataset using pandas.

### 3. Data Preprocessing

Separated:

- Independent Variable (X) → YearsExperience
- Dependent Variable (Y) → Salary

### 4. Train-Test Split

Split the dataset into:

- Training Set
- Testing Set

using train_test_split().

### 5. Model Training

Used:

LinearRegression()

to train the Simple Linear Regression model.

### 6. Prediction

Predicted salary values for test data using:

model.predict()

### 7. Visualization

Visualized:

- Training set results
- Test set results

using regression line plots.

---

## Output

The model successfully predicts salary based on years of experience.

It also generates a regression line showing the relationship between salary and experience.

---

## Sample Result

Example:

If experience = 5 years

Predicted Salary ≈ Based on trained model output

(The exact value depends on your dataset)

---

## Learning Outcomes

From this project, I learned:

- Basics of Machine Learning
- Supervised Learning
- Simple Linear Regression
- Data preprocessing
- Model training and testing
- Data visualization
- Real-world prediction problems

---

## Future Improvements

- Use larger real-world datasets
- Improve prediction accuracy
- Deploy the model using Flask/Streamlit
- Build a web app for live salary prediction

---

## Author

Harsha

B.Tech CSM (AI & ML) Student  
Aspiring AI Engineer

---

## GitHub Repository

This project is uploaded as part of my Machine Learning practice journey.

---
