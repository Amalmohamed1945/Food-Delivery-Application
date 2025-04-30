📦 Food Delivery Application – Data Science Project
📄 Abstract
This project analyzes a food delivery dataset to understand customer behavior, optimize delivery operations, and predict delivery time using machine learning models. The pipeline includes data cleaning, feature engineering, exploratory data analysis (EDA), and model evaluation to derive actionable insights for operational improvements.

📁 Dataset
The dataset used for this project is a synthetic but realistic dataset with the following key columns:

Order_Preparation_Time (min)

Delivery_Distance (km)

Order_Size (items)

Time_of_Day

Traffic_Condition

Weather

Delivery_Time (min) (target variable)

📌 File: food_delivery_cleaned_dataset.csv

🔧 Project Steps
Data Cleaning and Preprocessing

Handled missing values

Categorical encoding (LabelEncoding/OneHotEncoding)

Feature scaling (StandardScaler)

Exploratory Data Analysis (EDA)

Distribution plots for numeric and categorical features

Sunburst plots to visualize hierarchical relationships

3D scatter plot to analyze multivariate correlations

Feature Engineering

Created interaction features

Normalized continuous variables

Encoded time-of-day and weather patterns

Modeling and Evaluation

Trained multiple regression models to predict Delivery_Time (min)

Models: Linear Regression, Decision Tree, Random Forest

Metrics: RMSE, MAE, R²

📊 Model Performance

Model	RMSE	MAE	R²
Linear Regression	0.354	0.298	0.87
Decision Tree	0.482	0.390	0.79
Random Forest	0.430	0.351	0.83
📌 Key Insights
Linear Regression was the best performing model with high accuracy and efficiency (R² = 0.87).

Decision Tree overfit the training data and failed to generalize.

Random Forest proved robust and slightly more accurate than Decision Tree, with strong generalization capabilities.

Traffic, distance, and order size are the most influential features impacting delivery time.

🛠️ Tools Used
Python (Pandas, NumPy, Scikit-learn)

Plotly for interactive visualizations

Google Colab for experimentation

Matplotlib & Seaborn for data visualization

📁 Folder Structure
Copy
Edit
📂 food-delivery-analysis
├── food_delivery_cleaned_dataset.csv
├── model_results.ipynb
├── eda_visualizations.ipynb
└── README.md
