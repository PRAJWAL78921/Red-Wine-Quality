# Red Wine Quality Prediction

## Project Overview
This project aims to predict the quality of red wine based on various chemical properties such as acidity, citric acid content, sugar levels, and more.  
By analyzing these factors, the goal is to classify whether the wine is of good or bad quality, providing valuable insights for a wine manufacturing company planning to create a new brand.  

## Problem Statement
A wine manufacturing company wants to assess the quality of its wine using several chemical parameters.  
The objective is to determine if the wine quality is satisfactory based on these chemical properties, aiding in the decision-making process for creating a new brand.  

## Dataset
The dataset used for this project includes chemical properties of different wine samples and their corresponding quality ratings.  
It contains **1,599 observations** with **12 features**:  

- **fixed acidity**  
- **volatile acidity**  
- **citric acid**  
- **residual sugar**  
- **chlorides**  
- **free sulfur dioxide**  
- **total sulfur dioxide**  
- **density**  
- **pH**  
- **sulphates**  
- **alcohol**  
- **quality** (target variable)  

---

## Project Steps

### 1. Data Collection  
- Loaded the dataset using **Pandas** and explored its structure and content.  

### 2. Data Analysis and Visualization  
- Conducted **Exploratory Data Analysis (EDA)** to understand the distribution of variables and their impact on wine quality.  
- Visualized relationships between **wine quality** and various chemical properties using **bar plots** and **heatmaps**.  
- Plotted a **correlation heatmap** to identify the most significant features affecting wine quality.  

### 3. Data Preprocessing  
- Handled **outliers** using user-defined functions to ensure data is clean and suitable for modeling.  
- Applied **label binarization** to transform the quality ratings into **binary classes** (good quality vs. bad quality).  

### 4. Feature Importance  
- Used the **ExtraTreesClassifier** to evaluate the importance of different features in predicting wine quality.  

### 5. Modeling  
Built and evaluated various classification models, including:  

- **Random Forest Classifier**  
- **Logistic Regression**  
- **K-Nearest Neighbors (KNN)**  
- **Support Vector Classifier (SVC)**  
- **Decision Tree Classifier**  
- **Gaussian Naive Bayes (GNB)**  
- **XGBoost Classifier**  

- Compared the performance of these models using **accuracy scores** and **confusion matrices**.  

### 6. Results  
- Achieved the highest accuracy with the **Random Forest Classifier at approximately 89.58%**.  
- Constructed a **predictive system** using the trained model to classify wine quality based on user input.  

### 7. Conclusion  
- The project demonstrates that **certain chemical properties, such as alcohol content and sulphates, have a significant impact on wine quality**.  
- The developed model can assist the company in **quality control and product development decisions**.  

---

## Future Work  
- Explore additional **machine learning techniques** such as **ensemble methods** to further improve prediction accuracy.  
- Experiment with different **feature engineering methods** and **hyperparameter tuning** for better model performance.  
- Extend the analysis to include **other wine varieties** and create a comprehensive **wine quality prediction system**.  

## Technologies Used  
- **Python** (Pandas, Numpy, Scikit-learn, Seaborn, Matplotlib)  
- **Machine Learning algorithms**: Random Forest, Logistic Regression, SVM, etc.  
- **Interactive Visualization**: Developed **Tableau dashboards** for insights into wine quality and business optimization.  
