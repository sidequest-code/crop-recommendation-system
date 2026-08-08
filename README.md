# 🌱 Crop Recommendation System

An end-to-end Machine Learning web application built with **Flask** and **Scikit-Learn** that predicts the most suitable crop to cultivate based on soil parameters and weather conditions.

---

## ✨ Features

- **Input Parameters:** Takes Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, pH, and Rainfall.
- **Machine Learning Model:** Uses a trained model to make accurate crop predictions.
- **Web Interface:** Built with HTML, CSS, and Flask (Jinja2 templates).

---

## 📁 Project Structure

```text
crop-recommendation-system/
│
├── static/
│   ├── crop.jpg          # UI Background Image
│   └── styles.css        # Stylesheet
├── templates/
│   └── index.html        # Main Web Interface
├── app.py                # Flask Server Code
├── model.py              # ML Model Script
├── model.pkl             # Trained ML Model
├── Crop_recommendation.csv # Dataset
├── requirements.txt      # Dependencies
└── README.md             # Documentation