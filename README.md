## Starbucks Capstone Challenge

``Project Overview``


This project analyzes customer behavior on the Starbucks rewards mobile app. Starbucks frequently sends promotional offers to users, and the goal is to determine which demographic groups respond best to different types of offers. The analysis leverages machine learning techniques to predict user behavior and optimize promotional strategies.

``Dataset``

The dataset consists of three JSON files:

**portfolio.json**: Contains details of promotional offers such as type, duration, reward, and distribution channels.

**profile.json**: Contains customer demographic data including age, gender, income, and membership details.

**transcript.json**: Contains event logs tracking user interactions with offers, including when they were received, viewed, or completed.


Problem Statement

The key challenge is to analyze user behavior and predict which users are most likely to respond to a given offer. This can help Starbucks personalize offers and improve marketing efficiency.

``Methodology``

**Data Preprocessing**: Handling missing values, encoding categorical variables, and feature engineering.

**Exploratory Data Analysis (EDA)**: Understanding user behavior patterns and offer effectiveness.

**Feature Engineering**: Creating meaningful features for machine learning models.

**Model Selection**: Training and evaluating different machine learning models such as Random Forest, Logistic Regression, and Gradient Boosting.

**Evaluation**: Using precision, recall, and F1-score to measure model performance.

``Key Findings``

- **BOGO and discount offers** have different effectiveness based on user demographics.

- **Higher-income users** are more likely to respond positively to promotional offers.

- Users who actively engage with the Starbucks app are more likely to complete offers.

``Technologies Used``

1. Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
2. Jupyter Notebook
3. Machine Learning (Random Forest, Logistic Regression, Gradient Boosting)


## How to Use This Repository


``Clone the repository:``

1. git clone https://github.com/IntriguedCuriosity/Udacity_Capstone_Starbucks.git

2. Install dependencies:
  pip install -r requirements.txt

3. Run the Jupyter Notebook


``License``
This project is licensed under the MIT License - see the LICENSE file for details.
