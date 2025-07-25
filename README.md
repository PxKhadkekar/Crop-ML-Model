# 🌾 Crop Recommendation System using Machine Learning

This project predicts the most suitable crop to grow based on soil and weather conditions like nitrogen, phosphorus, potassium, temperature, humidity, pH, and rainfall. It uses a Random Forest Classifier and provides a user-friendly web interface using **Gradio**.

---

## 🔍 Overview

🚀 **Goal**: Help farmers and agricultural planners make data-driven decisions for crop cultivation.

🧠 **Model**: Random Forest Classifier (Scikit-learn)

🌐 **UI**: Built with Gradio – no coding needed to use it!

---

## 📊 Dataset

- 📁 **Source**: [Kaggle – Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)
- 🔢 **Features**:
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Temperature (°C)
  - Humidity (%)
  - pH
  - Rainfall (mm)
- 🎯 **Target**: Crop label (e.g., rice, maize, cotton)

---

## 🛠️ Installation & Usage

1. **Clone the repository or use the notebook in Google Colab**

2. **Install required libraries**
   ```bash
   pip install pandas numpy scikit-learn gradio opendatasets
