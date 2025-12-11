# CI_Assignment2
CSC3034 Computation Intelligence Assignment 2

# 🌾 Crop Recommendation using Artificial Neural Networks (ANN)

This project implements an Artificial Neural Network (ANN) to classify 22 different crop types based on environmental and soil parameters. The model is trained on the publicly available **Crop Recommendation Dataset**, which contains features such as nitrogen (N), phosphorus (P), potassium (K), temperature, humidity, pH, and rainfall.

---

## 🔍 Project Overview
The goal is to build a predictive model that recommends the most suitable crop given soil nutrient levels and weather conditions. An ANN is used due to its ability to model complex, non-linear relationships in agricultural data.

---

## 🧠 ANN Architecture
The implemented feedforward neural network consists of:

- **Input Layer:** 7 features  
- **Hidden Layer 1:** 64 neurons (ReLU)  
- **Hidden Layer 2:** 32 neurons (ReLU)  
- **Output Layer:** 22 neurons (Softmax for multi-class classification)

---

## ⚙️ Tech Stack
- Python  
- PyTorch  
- scikit-learn  
- NumPy / Pandas  

---

## 📊 Results
- **Test Accuracy:** ~99%  
- Strong performance across all 22 crop classes  
- Confusion matrix and classification report included in the output  

---

