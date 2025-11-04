# House-Price-Pricidiction-skillcraft
🏠 House Price Prediction using Linear Regression
📘 Project Overview

This project aims to predict house prices based on key property features using Linear Regression.
It uses the Ames Housing Dataset (Kaggle’s "House Prices: Advanced Regression Techniques") and focuses on a subset of important variables:

GrLivArea – Above ground living area (sq.ft)

BedroomAbvGr – Number of bedrooms above ground

FullBath – Number of full bathrooms

SalePrice – Target variable (house sale price)

This project is part of my Machine Learning Internship Task 01, where the goal is to build, train, and evaluate a regression model end-to-end.

🎯 Objectives

Analyze and clean the dataset

Understand correlations between features and target

Build and train a Linear Regression model

Evaluate model performance using R² and RMSE

Visualize actual vs predicted house prices

Generate final predictions on test data for submission

🧩 Dataset Details

Files used:

train.csv — Training dataset with features and target variable

test.csv — Test dataset (without target) for final predictions

data_description.txt — Explanation of all feature columns

sample_submission.csv — Format for submission file

Key Features Used:

Feature	Description
GrLivArea	Above ground living area (sq.ft)
BedroomAbvGr	Bedrooms above ground
FullBath	Full bathrooms above ground
SalePrice	Target variable (House price)
⚙️ Technologies Used

Python 3

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

🚀 Steps to Run the Project
1️⃣ Clone or Download the Repository
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction

2️⃣ Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

3️⃣ Place the Dataset Files

Ensure the following files are in the same directory:

train.csv
test.csv
data_description.txt
sample_submission.csv

4️⃣ Run the Project

You can execute the notebook or Python script:

python house_price_prediction.py


OR open in Jupyter Notebook:

jupyter notebook House_Price_Prediction.ipynb

📊 Model Workflow

Data Loading & Cleaning

Import dataset using Pandas

Handle missing values

Select relevant columns

Exploratory Data Analysis (EDA)

Correlation heatmap

Visualize feature relationships

Feature Engineering & Scaling

Standardize input features

Model Building

Train Linear Regression model

Model Evaluation

Compute R² Score & RMSE

Plot Actual vs Predicted Sale Prices

Final Prediction

Predict SalePrice for test.csv

Save results as submission.csv

📈 Example Results
Metric	Value
R² Score	~0.78
RMSE	~19000

Observations:

Strong positive correlation between GrLivArea and SalePrice.

Bedrooms and bathrooms add value, but living area is the most significant factor.

💡 Business Insights

Larger living areas lead to higher sale prices.

More bathrooms slightly improve price prediction accuracy.

Realtors and analysts can use this model for property price estimation and trend analysis.

🧾 Output Files

submission.csv — Predicted sale prices for test dataset

House_Price_Prediction.ipynb — Full notebook with code, visualizations, and explanations

README.md — Project documentation (this file)

🙌 Author

Omkar Mungade
Machine Learning Intern
📧 mungadeomkar9@gmail.com

🔗 [LinkedIn Profile : linkedin.com/in/omkar-mungade-114593316 ]
