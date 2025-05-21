# 🍷 Red Wine Quality Classification

This project explores the *Red Wine Quality dataset* from Kaggle, aiming to predict whether a red wine is of good quality or not using a variety of classification models.

Each wine in the dataset is rated on a quality scale from 0 to 10. For simplicity, this task redefines the target variable into a *binary classification problem*:

- *Good Quality*: Rating ≥ 7  
- *Not Good Quality*: Rating < 7  

## 🧪 Features

The model uses 11 physicochemical properties of the wine as input features:

- Fixed Acidity  
- Volatile Acidity  
- Citric Acid  
- Residual Sugar  
- Chlorides  
- Free Sulfur Dioxide  
- Total Sulfur Dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  

These features are used to train and evaluate several machine learning classifiers.

## 🎯 Objectives

The main goals of this project are:

- ✅ To experiment with multiple classification algorithms and compare their performance  
- ✅ To identify the most significant features that influence wine quality  
- ✅ To create an end-to-end data science pipeline from preprocessing to model selection  

## 🛠 Workflow

Here’s an overview of the steps followed in this project:

1. *Import Libraries* – Setting up the environment  
2. *Load the Dataset* – Reading in the CSV file  
3. *Data Exploration* – Getting a feel for distributions, correlations, and summary statistics  
4. *Missing Values Check* – Ensuring data quality  
5. *Feature Engineering* – Creating the binary target and scaling inputs  
6. *Class Imbalance Analysis* – Understanding the distribution of good vs. bad wines  
7. *Model Preparation* – Splitting data into training and testing sets  
8. *Model Training & Evaluation* – Applying various classifiers (e.g., Logistic Regression, Random Forest, SVM, etc.)  
9. *Model Selection* – Choosing the best performing model based on accuracy and other metrics  

## 📊 Results & Insights

- *Top Features*: Alcohol, Sulphates, and Volatile Acidity emerged as key predictors of wine quality.  

## 🥂 Conclusion

This project provided valuable insights into wine quality prediction using machine learning. With a well-tuned model and proper feature analysis, it's possible to distinguish good wines from average ones using chemical characteristics alone.

---

If you found this useful or interesting, feel free to ⭐ the repo — cheers!
