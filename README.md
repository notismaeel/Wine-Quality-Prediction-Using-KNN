# 🍷 Wine Quality Prediction – Streamlit App (KNN)

A machine learning web application that predicts **wine quality** based on physicochemical properties using the **K-Nearest Neighbors (KNN)** algorithm.  
Built with **Python, Streamlit, and Scikit-Learn**.

---

## 🌐 Live Demo

👉 **Streamlit App Link:**  
https://wine-quality-prediction-using-knn-axvphwoi8wmxwhv7mfuunw.streamlit.app/

---

## 📌 Project Overview

This project allows users to:

- Adjust wine chemical features using interactive sliders  
- Use a trained **KNN classifier** to predict wine quality  
- Visualize sample dataset inside the app  
- Perform real-time inference with standardized inputs  

The model is trained on the **WineQT dataset**, using features such as:

- Fixed acidity  
- Volatile acidity  
- Citric acid  
- Residual sugar  
- Chlorides  
- Alcohol  
- pH  
- Sulphates  
- Density  

---

## 🧠 Machine Learning Approach

- **Algorithm:** K-Nearest Neighbors (KNN)  
- **Preprocessing:** StandardScaler  
- **Train/Test Split:** 80% / 20%  
- **Target Variable:** Wine quality (integer score)  

---

## 🛠 Technologies Used

- Python  
- Streamlit  
- Pandas  
- Scikit-Learn  
- NumPy  

---

## 🚀 How to Run Locally

### 1. Clone the repository

```bash
git clone 
gh repo clone notismaeel/Wine_Quality_Prediction_KNN
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the app

```bash
streamlit run wine_knn_app.py
```

---

## 📂 Project Structure

```
├── wine_knn_app.py       # Main Streamlit application  
├── WineQT.csv            # Dataset  
├── requirements.txt      # Dependencies  
└── README.md             # Project documentation  
```

---

## 📊 Features

- Interactive sidebar sliders for all input variables  
- Real-time prediction using KNN model  
- Display of dataset preview  
- Clean and intuitive user interface  

---

## 🎯 Future Improvements

- Add model comparison (SVM, Random Forest, XGBoost)  
- Include exploratory data visualization charts  
- Add model performance metrics (accuracy, confusion matrix)  
- Enable file upload for batch prediction  

---

## 👤 Author

**Ismail**  
- GitHub: https://github.com/notismaeel  
- Email: ismveelll999@gmail.com  

---

## 📜 License

This project is for educational purposes.
