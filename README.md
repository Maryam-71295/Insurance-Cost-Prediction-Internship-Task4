# Insurance-Cost-Prediction-Internship-Task4
🏥 Insurance Cost Prediction using Machine Learning

📌 Introduction
The healthcare industry generates vast amounts of data that can be leveraged to improve decision-making and cost estimation. Accurately predicting medical insurance charges is essential for insurance providers to manage risk and for individuals to better understand potential healthcare expenses. This project applies machine learning techniques to estimate insurance claim amounts based on personal and demographic attributes.

🎯 Problem Statement
The objective of this project is to predict medical insurance charges using features such as age, BMI, smoking status, and other personal information. The task is formulated as a regression problem, where the goal is to model the relationship between input variables and the continuous target variable (charges).

📊 Dataset Description
Dataset: Medical Cost Personal Dataset
Total Records: 1338
Features:
age: Age of the individual
sex: Gender
bmi: Body Mass Index
children: Number of dependents
smoker: Smoking status
region: Residential area
charges: Medical insurance cost (target variable)

⚙️ Approach
🔹 Data Preprocessing
Checked for missing values and duplicates
Encoded categorical variables using One-Hot Encoding
Performed train-test split (80/20)
Applied feature scaling using StandardScaler (after split to prevent data leakage)

🔹 Exploratory Data Analysis (EDA)
Visualized relationships between:
Age vs Charges
BMI vs Charges
Smoking Status vs Charges
Generated correlation heatmap

🔹 Model Training
Implemented Linear Regression as the primary model

🔹 Evaluation Metrics
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)

📈 Key Insights
Smoking status is the most influential factor affecting insurance charges
Age has a strong positive correlation with medical costs
BMI shows moderate impact on charges
Region and gender have minimal influence

📊 Results
Linear Regression provides interpretable results but moderate accuracy
Ensemble models (Random Forest, Gradient Boosting) achieve higher predictive performance (~85–90% R²)
Proper preprocessing and scaling significantly improve model performance

✅ Conclusion
This project demonstrates how machine learning can be effectively used to predict insurance claim amounts. While Linear Regression offers simplicity and interpretability, more advanced models provide improved accuracy. The findings highlight that lifestyle factors, particularly smoking, play a critical role in determining healthcare costs. These insights can support better pricing strategies and risk assessment in the insurance industry.

🛠️ Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
