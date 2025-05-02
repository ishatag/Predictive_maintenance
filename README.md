# Predictive_maintenance
Predict machine failures (binary + multiclass) and identify failure types. Using the analysis, provide a summary to stakeholders.

🔧 Predictive Maintenance Using AI/ML

Project Type: Machine Learning (Binary & Multiclass Classification)
Tools & Libraries: Python, Pandas, Matplotlib, Seaborn, (AI Tools: Scikit-learn, XGBoost)

📌 Project Goal
The goal of this project is to develop AI/ML-driven models that can:

Predict whether a machine failure is likely to occur (Binary Classification)

Identify the specific type of failure if it does occur (Multiclass Classification)

This helps organizations minimize unplanned downtime, optimize maintenance schedules, and reduce costs by moving from reactive to predictive strategies.

📊 Dataset Overview
The dataset contains sensor data from industrial machines, with key features such as:

Temperatures, Speed, Torque, Tool Wear

Target (Failure Yes/No)

Failure Type (Tool Wear, Overstrain, Power Failure, etc.)

UDI (unique identifier) — dropped to prevent data leakage

🔍 Key Analyses
✅ 1. Binary Classification Model
Model: XGBoost
Task: Predict if a machine will fail (Yes/No)
Result:

Accuracy: 99%

Precision/Recall/F1 Score: > 0.98 for both classes

Confusion Matrix: Indicates highly reliable predictions

📈 Business Implication:
High-risk machines can be identified ahead of time. Stakeholders can prioritize intervention and reduce sudden breakdowns.

🎯 2. Multiclass Classification Model
Model: XGBoost (multi:softmax)
Task: Predict the type of failure (5 categories)
Result:

Strong classification report

Visual insights from confusion matrix and heatmaps

Dropped Product ID columns due to high correlation, avoiding overfitting

📈 Business Implication:
Allows root-cause maintenance, reducing unnecessary repairs and improving spare part management.

📈 Graphs & Tables - Key Insights
Correlation Heatmaps: Identified highly correlated product IDs — dropped for model clarity

Confusion Matrix: Displayed precise predictions across all failure types

Classification Reports: Provided F1 scores and precision/recall breakdowns

💼 Business Recommendations

Recommendation	Benefit      
1. 🔥 Focus on “Hot Leads” (high-risk machines)	Prevent critical failures
2. 🗓️ Schedule targeted maintenance	Reduce unnecessary service calls
3. 🧾 Optimize spare part inventory	Lower carrying costs
4. ⚙️ Improve sensor-based alerts	Enable real-time failure prevention
5. 📉 Use failure-type prediction	Enable cause-specific intervention

💬 Final Outcome
This project demonstrates how machine learning can revolutionize industrial maintenance by moving from reactive to predictive workflows. The binary model allows for early detection, while the multiclass model provides actionable insights into the failure type.

