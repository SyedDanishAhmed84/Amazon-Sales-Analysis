# 📦 Amazon Sales Performance Analysis with Regression & Classification
This project presents a comprehensive analysis of Amazon sales data using both regression and classification techniques. The dataset, sourced from Kaggle, includes over 5,000 records covering various aspects of product sales, pricing, discount, and profit metrics. The objective was to uncover insights, predict profit margins, and classify sales based on profitability.

## 📊 Exploratory Data Analysis & Visualization
- To explore relationships among key numerical features, I utilized Seaborn’s pairplot() functionality:

- Conducted multivariate visual analysis across variables including Unit Price, Quantity Sold, Discount (%), Total Sales, and Profit Margin.

- Applied focused pairplots to examine how Profit Margin responds to changes in Unit Price, Quantity Sold, and Total Sales.

## 📈 Predictive Modeling – Linear Regression
A Linear Regression model was developed to predict the Profit Margin based on:

- Unit Price

- Quantity Sold

- Total Sales

**Model performance was assessed using:**

- Mean Squared Error (MSE) – to quantify prediction error

- F1 Score – used for evaluation when predictions were thresholded for classification context

## 🤖 Classification Modeling – Logistic Regression
To identify whether a sale was high-profit or low-profit, I created a new binary feature named Profit_Label, where:

- Sales with a Profit Margin above a specified threshold were labeled as 1

- Others were labeled as 0

This enabled binary classification using Logistic Regression. **The model was evaluated using:**

- Classification Report

- Precision, Recall, and F1 Score

**Confusion Matrix, including analysis of:**

- True Positives (TP)

- True Negatives (TN)

- False Positives (FP)

- False Negatives (FN)

## 🎯 Key Outcomes
- Visualized multivariate relationships using Seaborn pairplots, enhancing understanding of feature interactions

- Successfully predicted profit margins using a regression model with meaningful accuracy

- Engineered a custom classification label to separate profitable vs. non-profitable sales

- Evaluated model performance using a comprehensive set of classification metrics

## 🛠️ Technologies Used
- Python

- Pandas -  data manipulation

- Matplotlib - data visualization

- Seaborn – multivariate visualization using pairplot()

- Scikit-learn – machine learning models and evaluation

- Jupyter Notebook – analysis environment

## 👨‍💻 Author
**Syed Danish Ahmed**

**Aspiring Data Scientist | Computer Engineering Student**

If you found this project helpful or insightful, consider giving it a ⭐ star , your support is appreciated!

