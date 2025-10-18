🫀 Heart Stroke Predictor System

A machine learning web app that predicts the risk of heart disease based on patient health indicators.
Built using Python, scikit-learn, and Streamlit — with full preprocessing, model training, and an interactive frontend.

🚀 Features

Full EDA (Exploratory Data Analysis) and Data Cleaning

Encodes categorical data using One-Hot Encoding

Trains multiple models:

Logistic Regression

KNN (final model)

Naive Bayes

Decision Tree

SVM (RBF Kernel)

Automatically saves best-performing model (KNN_heart.pkl), scaler, and columns

Interactive Streamlit frontend for live predictions

📊 Dataset

The dataset (heart.csv) contains health metrics of patients:

Feature	Description
Age	Patient age
Sex	M / F
ChestPainType	Type of chest pain (ATA, NAP, TA, ASY)
RestingBP	Resting Blood Pressure
Cholesterol	Serum Cholesterol
FastingBS	Fasting Blood Sugar > 120 mg/dL (0 or 1)
RestingECG	Resting ECG results
MaxHR	Maximum Heart Rate Achieved
ExerciseAngina	Exercise Induced Angina (Y/N)
Oldpeak	ST Depression
ST_Slope	ST Segment Slope
HeartDisease	Target variable (1 = Yes, 0 = No)
🧠 Model Training

Cleaned and preprocessed using Pandas and NumPy

Features scaled using StandardScaler

Evaluated models using Accuracy and F1-score

Best Performing Model:
✅ KNN Classifier — Accuracy: 86.4%, F1-score: 0.88

All training notebooks are included:

StrokePredictor.ipynb

AllProcessesBeforeModelCreation.ipynb

DataVisualisation.ipynb

etc.

💻 Streamlit App

Interactive prediction interface:

streamlit run app.py

Inputs

Age, Gender, Chest Pain Type, Blood Pressure, Cholesterol, etc.

Output

🟥 “High Risk of Heart Disease”

🟩 “Low Risk of Heart Disease”

🗂️ Project Structure
Machine-Learning/
│
├── StrokePredictor.ipynb
├── app.py
├── heart.csv
├── KNN_heart.pkl
├── scaler.pkl
├── columns.pkl
└── README.md

🧰 Tech Stack

Python 3.12

Streamlit

scikit-learn

Pandas

NumPy

Matplotlib / Seaborn

Joblib

⚙️ Installation

Clone the repo:

git clone https://github.com/iraj259/Machine-Learning.git
cd Machine-Learning


Install dependencies:

pip install -r requirements.txt


Or manually install the key packages:

pip install streamlit scikit-learn pandas numpy seaborn matplotlib joblib


Run the app:

streamlit run app.py

📈 Example Output

Model trained and evaluated with results:

Model	Accuracy	F1 Score
Logistic Regression	0.8696	0.8857
KNN	0.8641	0.8815
Naive Bayes	0.8533	0.8683
Decision Tree	0.788	0.8098
SVM (RBF Kernel)	0.8478	0.8679
👨‍💻 Author

Iraj — Computer Science Student
📍 Passionate about ML, Data Science, and AI-driven applications.
GitHub Profile →

🧾 License

This project is open-source under the MIT License.