# 🚚 Delivery Time Trend Prediction Using Machine and Deep Learning

A project to analyze and predict delivery times using machine learning and deep learning models, enhanced with geospatial data.

---

## 📌 Project Overview

- 🗺️ Integrated geospatial information to improve delivery time predictions
- 📊 Performed data cleaning, feature engineering, and exploratory analysis
- 🤖 Trained and evaluated models using Scikit-learn and TensorFlow
- 🧠 Compared ML and DL approaches to capture nonlinear delivery patterns

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- GeoPandas
- Matplotlib, Seaborn
- Jupyter Notebook

---
## 📁 Project Structure
```
delivery-time-prediction/
├── delivery_time_prediction.ipynb
├── dataset/
│ └── deliveries_with_location.csv
├── models/
│ └── deep_learning_model.h5
└── README.md
```
---

## 🧪 Models Used

- Decision Tree
- Random Forest Regressor
- XG Boost
- Conventional Neural Network

## 📈 Model Performance

| Algorithm                     | R² Score | Mean Squared Error |
|------------------------------|----------|---------------------|
| Random Forest                | 0.9005   | 8.78                |
| Decision Tree                | 0.9911   | 0.78                |
| XGBoost                      | 0.5244   | 41.95               |
| Convolutional Neural Network | 0.2843   | 63.12               |

---

## 📈 Key Insights

- Geospatial features (distance, region, coordinates) significantly improve prediction accuracy
- Deep learning models performed better in capturing complex patterns in location-related delivery delays

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/delivery-time-trend-prediction.git
   cd delivery-time-trend-prediction

2. Launch Jupyter Notebook:
- jupyter notebook delivery_time_prediction.ipynb

3. Run all cells to perform data preprocessing, model training, and result analysis.

📬 Contact
- Kishore N
- 📧 kishoren15404@gmail.com
- 🔗 linkedin.com/in/kishoren

📄 License
This project is licensed under the MIT License.
