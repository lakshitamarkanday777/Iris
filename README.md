# 🌸 Iris Flower Prediction Web App using Streamlit

This project is a beginner-friendly machine learning deployment tutorial that demonstrates how to build and deploy a web application using **Streamlit**. The model predicts the species of Iris flowers based on user-provided measurements.

## 📌 Project Overview

- **Course**: NorQuest College – Machine Learning Analyst Diploma  
- **Tutorial Focus**: Model deployment using Streamlit  
- **Use Case**: Classify iris flower species  
- **Model Used**: Random Forest Classifier (sklearn)

## 🌱 About the App

This simple app allows users to interact with sliders to input values for sepal and petal dimensions, and returns the predicted Iris species in real-time.

### Features:
- Slider-based input for sepal and petal dimensions
- Real-time predictions using a trained Random Forest model
- Display of prediction probabilities
- Interactive UI with `streamlit`

## 🔍 User Input Parameters

| Feature         | Description                       |
|----------------|-----------------------------------|
| `sepal_length` | Length of sepal (cm)              |
| `sepal_width`  | Width of sepal (cm)               |
| `petal_length` | Length of petal (cm)              |
| `petal_width`  | Width of petal (cm)               |

## 🧠 Model Details

- **Dataset**: scikit-learn's built-in Iris dataset
- **Algorithm**: Random Forest Classifier
- **Training**: Done in-app (not pre-saved model)
- **Output**: Predicted flower species + probability distribution

## 💻 How to Run

### 1. Install Required Libraries

```bash
pip install streamlit scikit-learn pandas numpy
