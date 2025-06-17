# 🎯 Student Score Predictor - Linear Regression Project

This project showcases a simple machine learning model built using **Linear Regression** to predict student exam scores based on the number of hours they study. It is an ideal beginner project for those starting with Supervised Learning and helps understand the complete ML workflow — from data preprocessing to model evaluation and prediction.

---

## 🧠 Objective

To predict a student’s exam score using the number of hours they studied, by training a **Linear Regression** model. This demonstrates the application of **supervised machine learning (regression)**.

---

## 📁 Dataset Information

- **Dataset Source**: [Student Scores CSV (GitHub)](https://raw.githubusercontent.com/AdiPersonalWorks/Random/master/student_scores%20-%20student_scores.csv)
- **Features**:
  - `Hours`: Number of hours a student studies
  - `Scores`: Marks obtained by the student in the test

---

## 🔧 Technologies and Libraries Used

| Tool | Purpose |
|------|---------|
| Python | Programming language |
| Pandas | Data handling and analysis |
| Matplotlib | Data visualization |
| Scikit-learn | Model building and evaluation |

---

## 🔍 Project Workflow

### 1. Data Loading
- The dataset is loaded using `pandas.read_csv()`

### 2. Exploratory Data Analysis
- A scatter plot is created using `matplotlib.pyplot` to visualize the correlation between hours and scores

### 3. Data Preprocessing
- Features (`X`) and label (`y`) are extracted
- Data is split into training and testing sets using `train_test_split` (80% train, 20% test)

### 4. Model Training
- A **Linear Regression model** is trained on the training data using `LinearRegression().fit()`

### 5. Prediction
- The trained model predicts scores for the test set
- It also predicts custom input, like the score for a student who studies for 9.25 hours

### 6. Model Evaluation
- Model accuracy is assessed using **Mean Squared Error (MSE)**

---

## 📈 Sample Output

```bash
   Actual  Predicted
0   88.0   87.61
1   60.0   60.14
2   85.0   83.84
3   95.0   94.89
4   30.0   28.41

Mean Squared Error: 18.94

Predicted Score for 9.25 hours of study: 93.69

