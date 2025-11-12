# 🎬 Movie Box Office Prediction (Linear Regression)

A machine learning model to predict the **Worldwide Box Office Collection (₹ crores)** of Indian movies using Linear Regression.

---

## 📘 Overview
This project estimates movie revenue based on production, creative, and release factors.  
It uses a dataset containing movie attributes such as budget, ratings, genre, and language distribution.

The model applies:
- **Weighted language & genre scoring**
- **Log transformation** for stability
- **Smart multilingual assignment** (based on movie tier)

---

## ⚙️ Features Used
- **Budget**
- **IMDb Rating**
- **Star Power, Music Hype, Director Index**
- **Runtime, Screen Count, Festive Month Flag**
- **Language Score**
- **Genre Score**

Target variable:  
> `Worldwide Gross Collection (log-transformed)`

---

## 🧠 Model Details
- **Algorithm:** Linear Regression  
- **Scaling:** StandardScaler  
- **Split:** 80% Train / 20% Test  
- **Metrics:** R², MAE, RMSE  

Typical results:
# Movie-Revenue-Prediction
