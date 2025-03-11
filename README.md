# health-4 Exploratory Data Analysis (EDA) was conducted to understand the dataset and key factors influencing heart disease.

🔹 Data Cleaning & Distribution Analysis

Checked for missing values and handled them appropriately.
Visualized BMI, physical activity, smoking, and diabetes distributions.

🔹 Target Variable (Heart Disease) Analysis

Identified class balance issues and considered mitigation strategies.
Observed that heart disease cases were more common in individuals with unhealthy lifestyles.

🔹 Feature Relationships & Insights

Higher BMI, smoking, and diabetes were strongly associated with heart disease.
Physically active individuals had a lower risk of heart disease.
Correlation analysis confirmed strong links between lifestyle factors and heart disease risk.

📌 Key Takeaway: The data suggests that maintaining a healthy weight, avoiding smoking, and staying physically active can significantly reduce heart disease risk.
This project builds a logistic regression model to predict heart disease based on BMI, physical activity, smoking, and diabetes status. The dataset is preprocessed using label and ordinal encoding, and the model is trained using Scikit-Learn.

Key Steps:
Data Preprocessing – Handle categorical variables and normalize BMI.
Model Training – Logistic regression to classify heart disease presence.
Evaluation – Accuracy, confusion matrix, and classification report.
Findings – Smoking, diabetes, and low physical activity increase heart disease risk.
Recommendations – Encourage exercise, healthy diet, quitting smoking, and regular checkups.

🔹 Future Enhancements: Improve model with Random Forest, add more health indicators, and deploy via Streamlit.
