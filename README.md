🏠 House Price Prediction

This project applies Machine Learning and Statistical Analysis to predict house prices based on various features such as area, number of rooms, location, and more. The project combines exploratory data analysis (EDA), statistical tests, and linear regression modeling to identify key factors that influence housing prices .

🚀 Features

* Exploratory Data Analysis (EDA) with visualization and correlation checks.
* Multicollinearity detection using Variance Inflation Factor (VIF).
* Feature selection techniques including Mutual Information Classifier.
  
* Statistical tests for feature significance:
 > Correlation analysis
 > Cramer’s V (categorical association)
 > ANOVA test (feature importance)
 >Levene’s test (variance homogeneity)
 > Linear Regression model .
 > Evaluation using metrics such as R², MAE, and RMSE.

📂 Project Structure

├── Ames_housing_data.csv                   # Dataset used for training and testing  
├── House_price_prediction.ipynb            # Jupyter Notebook with full workflow  
├── requirements.txt                        # Project dependencies  
└── README.md                               # Documentation  


📊 Results

* Identified the most significant factors affecting house prices.
* Checked assumptions of linear regression (normality, homoscedasticity, multicollinearity).

📌 Tech Stack

 * Python
 * Pandas, NumPy – data handling
 * Matplotlib, Seaborn – visualization
 * Scikit-learn – machine learning models and metrics
 * Statsmodels / Scipy – statistical tests
