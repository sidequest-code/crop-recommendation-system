# 🌱 Crop Recommendation System

An end-to-end Machine Learning web application built with **Flask** and **Scikit-Learn** that predicts the most suitable crop to cultivate based on soil parameters and weather conditions.

---

## ✨ Features

- **Input Parameters:** Takes Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, pH, and Rainfall.
- **Machine Learning Model:** Uses a trained model to make accurate crop predictions.
- **Web Interface:** Built with HTML, CSS, and Flask (Jinja2 templates).

---

## 📁 Project Structure

```
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


```
---

## 🚀 How to Run the Project

1. **Clone the repository:**
   ```
   git clone [https://github.com/sidequest-code/crop-recommendation-system.git](https://github.com/sidequest-code/crop-recommendation-system.git)
  
2. **Navigate into the project directory**:
```
cd crop-recommendation-system
```
3. **Install dependencies**:
```
pip install -r requirements.txt
```
4. **Run the Flask app**:
```
python app.py
```
5. **Open in browser**:
   
Navigate to http://127.0.0.1:5000/ in your web browser.

---
## 🎯 How to Use the App
1. Enter the required soil parameters (Nitrogen, Phosphorus, Potassium, and pH).

2. Enter the environmental conditions (Temperature, Humidity, and Rainfall).

3. Click Predict to see the recommended crop!
