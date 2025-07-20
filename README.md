🌍 Greenhouse Gas Emission Prediction using Machine Learning
📌 Project Overview
Predict CO₂ emissions based on country-wise economic and energy indicators using Machine Learning. This project demonstrates preprocessing, encoding categorical variables, building predictive models, and evaluating performance.

🛠️ Technologies & Libraries Used
🐍 Python

📊 pandas, numpy

📉 scikit-learn

📈 matplotlib, seaborn (for visualization)

📂 Dataset
Format: .csv

Features:

Year

Country (categorical)

CO2 Emissions (target)

GDP

Population

Energy Use

🧹 Data Preprocessing Steps
✅ Null value handling

✅ Dropping incomplete rows

✅ Categorical encoding using pd.get_dummies()

✅ Selecting relevant features

✅ Splitting into training and testing sets

🤖 Model Building
Algorithm Used: Linear Regression

Steps:

Train-test split (80-20)

Model training on training data

Performance evaluation on test data

📊 Evaluation Metrics
🔢 Mean Absolute Error (MAE)

🧮 Mean Squared Error (MSE)

💥 R² Score

🔍 Key Learnings
Importance of encoding categorical variables

Feature selection for better performance

Visualizing relationships using matplotlib and seaborn

Basic model evaluation and tuning

🚀 Future Improvements
Try advanced models like:

🧠 Random Forest

📦 XGBoost

Incorporate feature scaling for better performance

Use more granular and larger datasets

📸 Sample Output
📍 Predicted vs Actual CO2 Emissions
📍 R² Score: ~0.85 (example)
