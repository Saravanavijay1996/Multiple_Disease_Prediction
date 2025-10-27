## 🩺 Multiple Disease Prediction using Machine Learning

# 🔎 Project Overview 
The Multiple Disease Prediction System is an interactive Streamlit web application designed to predict the likelihood of various medical conditions — Kidney Disease, Liver Disease, and Parkinson’s Disease — using pre-trained Machine Learning models.

The app allows healthcare professionals and users to input patient health parameters through a simple UI and instantly receive disease risk predictions, probability scores, and categorized risk levels.

---

## ⚙️ Key Features

# ✅ Three-Disease Prediction Models

- 🧠 Parkinson’s Disease

- 💉 Kidney Disease

- 💊 Liver Disease

---

# ✅ Instant Predictions

- Predicts disease presence (Disease / No Disease)

- Displays prediction probability and risk level (Low / Moderate / High)

## ✅ Streamlit Dashboard

Intuitive interface with sidebar navigation

Real-time feedback and error handling

Optimized model loading using @st.cache_resource

---

## 🧩 Tech Stack

- Frontend/UI: Streamlit

- Backend/Logic: Python

## Libraries Used:

- pandas, numpy – Data handling

- joblib – Model loading

- scikit-learn – ML pipeline (pre-trained models)

- os – File path management

## 🧠 How It Works

- User selects a disease from the sidebar.

- Inputs required health parameters using interactive form fields.

- The pre-trained ML model for that disease is loaded via joblib.

## Model predicts:

- Probability of disease (e.g., 0.82 = 82%)

- Classification (Disease / No Disease)
