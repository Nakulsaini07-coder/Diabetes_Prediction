# Diabetes Prediction

A machine learning web app that predicts whether a person is diabetic or not based on health-related inputs. This project uses a classification model (SVM) and is deployed using Streamlit.

## 🔍 Problem Statement
Using a labeled medical dataset of patients, we aim to train a model that predicts diabetes using features like glucose level, BMI, insulin, etc. This helps in early detection and preventive care.

## 🚀 Project Overview
- Predicts diabetes using 8 medical attributes
- Built using Python, scikit-learn, pandas, numpy
- Simple web interface using **Streamlit**
- Model is trained and saved using `pickle`

## ✅ Results
- Model: SVM classifier with linear kernel 
- Accuracy: ~76%
- Evaluation: Accuracy score, basic analysis (Confusion Matrix & Classification Report can be added)

## 🧠 ML Pipeline
1. Load and preprocess the dataset
2. Train a classification model (SVM)
3. Save the trained model as `trained_model.pkl`
4. Load the model in `app.py` using `pickle`
5. Take user inputs via Streamlit UI and show prediction

## 📁 Files
- `Diabetes_Prediction.ipynb`: Main notebook
- Dataset: The dataset `diabetes.csv` is already included in this repository for easy access.
## 🚀 How to Run
1. Clone this repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook in Jupyter or Colab

## 📊 Future Improvements
- Add confusion matrix and classification report
- Try advanced models (Random Forest, XGBoost)
- Perform hyperparameter tuning (GridSearchCV)
