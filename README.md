# 🌾 Crop Recommendation System

This project uses a machine learning model to recommend the most suitable crop to grow based on soil and environmental conditions such as nitrogen, phosphorous, potassium, temperature, humidity, pH, and rainfall. The model is deployed using an interactive Gradio interface.

---

## 📌 Problem Statement

Farmers often struggle to determine the right crop for their soil due to the lack of scientific knowledge and tools. This project aims to solve this problem using machine learning by recommending the most suitable crop based on the current conditions of the soil and environment.

---

## 📊 Dataset

- **Source**: [Kaggle - Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)
- **Features**:
  - `N`, `P`, `K` – Soil nutrient contents
  - `Temperature`, `Humidity` – Environmental factors
  - `pH` – Acidity/alkalinity of the soil
  - `Rainfall` – Amount of rainfall in mm
- **Target**:
  - `label` – Recommended crop name

---

## 🚀 Technologies Used

- Python
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn (for training the ML model)
- Gradio (for the web-based user interface)

---

## 🧠 ML Model

- **Algorithm**: Random Forest Classifier  
- **Accuracy**: ~99%  
- **Evaluation**: Confusion matrix and classification report  

---

## 🖥️ How It Works

1. Load and preprocess the dataset.
2. Train a Random Forest classifier on 80% of the data.
3. Evaluate performance on the remaining 20%.
4. Predict crop based on user inputs.
5. Provide a simple GUI using Gradio sliders and buttons for real-time prediction.

---

## Accuracy: 0.99
✅ Recommended Crop: rice

