# Churn-Prediction-Business-Recommendations
Data Analytics project.
📄 Dataset Overview
The dataset contains 150 customers with the following features:

CustomerID

Gender

Age

TenureMonths

MonthlyCharges

TotalCharges

ContractType

SupportTickets

PaymentMethod

IsActive (Target: 1 = Active, 0 = Churned)

The goal is to analyze patterns and build a model to identify customers likely to churn.

📊 Exploratory Data Analysis (EDA)
The notebook includes the following visualizations:
Line Chart – Monthly Charges Trend
Bar Chart – Active vs Churned Customers
Histogram – Age Distribution
Box Plot – Charges by Contract Type
Scatter Plot – Monthly vs Total Charges
Correlation Heatmap
Pie Chart – Payment Method Distribution
Area Chart – Avg Monthly Charges by Tenure
These plots help understand customer behavior, spending patterns, and relationships between features.

🤖 Machine Learning Models
Models used:
Logistic Regression
Random Forest Classifier
Gradient Boosting / XGBoost (optional)
Train/Test split evaluation
Accuracy, Precision, Recall, F1-score
Model selection is based on performance and interpretability.

🧠 Explainability – SHAP Analysis
SHAP (SHapley Additive exPlanations) is used to:
Identify top features influencing churn
Visualize global and local explanations
Understand how each feature impacts predictions
This improves trust and transparency in the model.

📈 Key Results
The model successfully predicts churn probability for customers.
SHAP helps highlight which features strongly affect model output.
Visual insights reveal strong patterns across tenure, contract type, and billing behavior.

📁 How to Run the Project
1. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn shap jupyter

2. Launch Jupyter Notebook
jupyter notebook

3. Open the main notebook
Churn Prediction + Business Recommendations.ipynb

🎯 Project Goals
Understand customer behavior using visual analytics
Build a reliable churn prediction model
Provide explainable results using SHAP
Present insights in a clean and interpretable format

📌 Future Improvements
Add hyperparameter tuning
Deploy model using Flask or Streamlit
Integrate real-time churn prediction API
Add Power BI/Tableau dashboard
