# Multi-Disease-Prediction-Model
🩺 AI-Based Multi-Disease Prediction System

Website Link : https://multi-disease-prediction-model-ai-ml.onrender.com/
📌 Project Overview

The AI-Based Multi-Disease Prediction System is a Machine Learning application that predicts the risk of multiple health conditions using patient health parameters.

The system uses trained Machine Learning classification models to analyze medical attributes and provide risk predictions for:

Fever Prediction
Diabetes Prediction
Heart Attack Risk Prediction

The project includes complete ML workflow from data generation, model training, evaluation, and deployment using Streamlit.

🎯 Objective

The main objective of this project is to build an AI-powered healthcare prediction system that can:

Process patient health information
Apply Machine Learning algorithms for classification
Predict disease risk probability
Provide an interactive user-friendly interface

🛠️ Tech Stack
Programming Language
Python
Libraries & Frameworks
Pandas → Data processing
NumPy → Numerical computations
Scikit-learn → Machine Learning models
Joblib → Model serialization
Streamlit → Web application deployment


🤖 Machine Learning Models Used

Multiple classification algorithms were trained and compared:

Logistic Regression
Random Forest Classifier
Gradient Boosting Classifier
Support Vector Machine (SVM)

The best-performing model was selected based on accuracy and saved for prediction.

📂 Project Workflow
Data Generation
        |
        ↓
Data Preprocessing
        |
        ↓
Model Training
        |
        ↓
Model Evaluation
        |
        ↓
Best Model Selection
        |
        ↓
Streamlit Deployment


📊 Dataset

Since real medical datasets require privacy considerations, synthetic healthcare datasets were generated for experimentation.

Datasets created:

Fever Dataset

Features:

Temperature
Cough
Headache
Fatigue
Sore Throat
Muscle Ache

Target:

Fever Risk

Diabetes Dataset

Features:

Pregnancies
Glucose Level
Blood Pressure
BMI
Insulin
Age
Diabetes Pedigree Function

Target:

Diabetes Risk

Heart Disease Dataset

Features:

Age
Sex
Chest Pain Type
Cholesterol
Blood Pressure
Heart Rate
Exercise Angina
Other clinical parameters

Target:

Heart Attack Risk

🚀 Application Features

✅ Select disease type
✅ Enter patient health parameters
✅ Predict disease risk
✅ Display prediction probability
✅ Interactive Streamlit interface

The application loads trained ML models and performs real-time predictions.


📁 Project Structure
Multi-Disease-Prediction-System/

│
├── data_generator.py
├── model_train.py
├── model_test.py
├── app.py
│
├── fever_best_model.pkl
├── diabetes_best_model.pkl
├── heart_best_model.pkl
│
├── fever_data.csv
├── diabetes_data.csv
├── heart_data.csv
│
└── requirements.txt


▶️ How to Run Project
1. Clone Repository
git clone repository-url
2. Install Dependencies
pip install -r requirements.txt
3. Generate Dataset
python data_generator.py
4. Train Models
python model_train.py
5. Run Application
streamlit run app.py


📈 Future Improvements
Add real-time medical dataset integration
Improve model accuracy with advanced algorithms
Add explainable AI (SHAP/LIME)
Add user authentication
Deploy using cloud platforms


👩‍💻 Author

Khushi
Machine Learning | Data Analytics | Python

Machine Learning | Data Analytics | Python

GitHub ke liye ye README recruiter ko clearly dikhayegi ki tumne sirf model nahi banaya, balki complete ML pipeline + deployment kiya hai.
