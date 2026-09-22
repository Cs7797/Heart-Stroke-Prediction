# ❤️ Heart Disease Prediction

A machine learning web application that predicts the risk of heart disease based on a user's clinical and physiological parameters.

The project uses a **K-Nearest Neighbors (KNN)** classification model and provides an interactive interface built with **Streamlit**.

---

## 📌 Project Overview

Heart disease is one of the major health concerns worldwide. Machine learning can be used to analyze medical parameters and identify patterns associated with heart disease risk.

This project takes several patient attributes as input and uses a trained KNN classification model to predict whether the given input indicates:

- ✅ Low Risk of Heart Disease
- ⚠️ High Risk of Heart Disease

The model input is processed using the same preprocessing pipeline used during model training, including feature scaling and one-hot encoded categorical variables.


---
## Screenshots

<img width="1843" height="932" alt="Screenshot 2026-09-22 182800" src="https://github.com/user-attachments/assets/2aedc08d-86ae-4072-811c-20bc8b95676b" />
<img width="1837" height="908" alt="Screenshot 2026-09-22 182812" src="https://github.com/user-attachments/assets/f201d2ab-7104-466f-984a-481a974d514b" />


## ✨ Features

- Interactive web interface using Streamlit
- KNN-based heart disease prediction
- User-friendly input controls
- Numerical and categorical feature handling
- Feature scaling using a saved scaler
- Consistent feature ordering using saved column information
- Instant prediction results
- Simple and lightweight deployment

---

## 🧠 Machine Learning Model

### Algorithm

**K-Nearest Neighbors (KNN)**

KNN is a supervised machine learning algorithm used for classification. It predicts the class of a new data point based on the classes of its nearest data points in the feature space.

For this project:

```text
User Input
     ↓
Feature Preparation
     ↓
One-Hot Encoded Features
     ↓
Feature Scaling
     ↓
Trained KNN Model
     ↓
Prediction
     ↓
Heart Disease Risk
```
