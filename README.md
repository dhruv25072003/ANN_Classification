🔮 ANN Classification Projects

This repository contains two beginner-to-intermediate level Artificial Neural Network (ANN) projects built using TensorFlow/Keras — one for Customer Churn Prediction and another for Salary Prediction. Both include preprocessing, training, and deployment-ready code.

⸻

📌 Projects Included

1️⃣ Customer Churn Prediction

Predicts whether a customer is likely to leave a company based on historical data.

Features:
	•	Trained on Churn_Modelling.csv.
	•	Preprocessing: Label Encoding, One-Hot Encoding, and Feature Scaling.
	•	ANN built using Keras Sequential API.
	•	Saved model (model.keras) + scaler/encoders for reproducibility.
	•	Interactive Streamlit app (app.py) to test customer details and get real-time churn prediction.

Run it locally:

pip install -r requirements.txt
streamlit run app.py


⸻

2️⃣ Salary Prediction (Regression)

Predicts employee salary based on features like experience and level.

Features:
	•	Implemented in salary_regression.ipynb and salary_predictor.py.
	•	Regression-based ANN (instead of classification).
	•	Demonstrates how ANNs can adapt to continuous value prediction.
	•	Includes model training, evaluation, and inference code.

Run it locally:

python salary_predictor.py


⸻

📂 Repository Structure

File / Folder	Description
Churn_Modelling.csv	Dataset for churn prediction
experiments.ipynb	Model exploration for churn
predictions.ipynb	Sample predictions & testing
salary_regression.ipynb	Notebook for salary prediction
salary_predictor.py	Script for running salary model
app.py	Streamlit GUI for churn prediction
model.keras	Saved ANN model
scaler.pkl & encoders	Preprocessing tools
requirements.txt	Dependencies


⸻

🚀 Key Learnings
	•	Building and training ANNs for both classification & regression.
	•	Managing end-to-end pipelines: preprocessing → training → saving models.
	•	Creating user-facing apps with Streamlit for non-technical users.
	•	Understanding how ANNs generalize across problem types.