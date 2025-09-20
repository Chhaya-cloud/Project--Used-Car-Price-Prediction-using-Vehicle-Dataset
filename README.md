**Used Car Price Prediction** 🚗
**Project Overview**

This project focuses on predicting the selling price of used cars using a Vehicle Dataset. Car resale prices are influenced by multiple factors such as manufacturing year, kilometers driven, fuel type, transmission, seller type, and ownership history. By building robust regression models, this project aims to provide accurate price estimates, helping both buyers and sellers make informed decisions in the used car market.

**Problem Statement**

Determining a fair resale price for used cars is challenging due to variations in car age, mileage, brand, and other features. Traditional pricing methods may lead to overpricing or undervaluation. This project leverages machine learning techniques to build models capable of predicting reliable selling prices.

**Objectives**

Build and optimize regression models (Linear Regression, Random Forest, XGBoost) for used car price prediction.

Perform data preprocessing, feature engineering, and exploratory data analysis (EDA).

Conduct hyperparameter tuning to improve model performance.

Evaluate models using regression metrics such as R² Score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

Analyze feature importance to understand key drivers of car prices.

 **Dataset**

**Source**: Vehicle Dataset (Kaggle / provided dataset)
**Features**:

Name (Car Make & Model)

Year of Manufacture

Kilometers Driven

Fuel Type (Petrol, Diesel, CNG)

Seller Type (Individual, Dealer)

Transmission (Manual, Automatic)

Owner (First, Second, Third, etc.)
Target: Selling Price (INR or USD depending on dataset)

**Methodology**
Data Preprocessing

Handling missing values and duplicate records.

Encoding categorical variables using One-Hot Encoding or Target Encoding.

Feature engineering (e.g., car age, mileage per year, brand extraction).

Scaling numerical features for model stability.

Exploratory Data Analysis (EDA)

Visualizing selling price distribution to identify outliers.

Analyzing relationships such as selling_price vs. car_age and selling_price vs. km_driven.

Evaluating the impact of categorical features like fuel type, transmission, and seller type.

**Modeling**

Built and compared multiple regression models:

Linear Regression

Random Forest Regressor

XGBoost Regressor

Hyperparameter tuning performed for tree-based models to optimize depth, number of estimators, and learning rate.

**Evaluation**

Metrics: R² Score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)

Predicted vs. actual price visualizations to assess model fit.

Feature importance analysis to determine which factors influence car prices the most.
 **Results**

Random Forest Regressor showed the best performance with significant improvement over Linear Regression.

Car age, kilometers driven, brand, and fuel type were identified as the most influential features.

Model evaluation confirmed its ability to generalize well to unseen data and provide reliable price estimates.

**Tech Stack**

Programming: Python

Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost

Tools: Jupyter Notebook

**Future Improvements**

Include additional features like car engine size, horsepower, and accident history.

Integrate location-based pricing factors.

Deploy the model via Streamlit or Flask for real-time price predictions.

Explore ensemble and stacking techniques to further improve accuracy.

 **Acknowledgements**

Special thanks to the dataset contributors and the open-source community for providing tools and libraries that made this project possible.
