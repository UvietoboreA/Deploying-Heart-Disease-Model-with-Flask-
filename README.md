# 🫀 Deploying Heart Disease Model - Flask Web App 

## 🚀 Overview  
This project is a **machine learning-powered web application** that predicts the likelihood of heart disease based on user inputs. It is built using **Flask**, a lightweight web framework for Python, and leverages a **Random Forest** model for predictions. The dataset used for training contains various health-related parameters that influence heart disease risk.  

---

## 📌 Features  
✅ **Machine Learning Model** (Random Forest) trained on heart disease data  
✅ **Flask-based Web Application** for real-time predictions  
✅ **User-friendly Interface** with interactive input fields  
✅ **Data Preprocessing** (Ordinal Encoding, MinMax Scaling)  
✅ **Deployed Model** using `pickle` for fast inference  

---

## 📊 Dataset Details  
The model is trained on a **Heart Disease Dataset**, which includes the following **features**:  

| Feature | Description |
|---------|------------|
| `age` | Age of the individual |
| `sex` | Gender (1 = Male, 0 = Female) |
| `cp` | Chest pain type (Categorical: 0-3) |
| `trestbps` | Resting blood pressure (mm Hg) |
| `chol` | Serum cholesterol (mg/dl) |
| `fbs` | Fasting blood sugar (>120 mg/dl, 1 = True, 0 = False) |
| `restecg` | Resting electrocardiographic results |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina (1 = Yes, 0 = No) |
| `oldpeak` | ST depression induced by exercise relative to rest |
| `slope` | Slope of the peak exercise ST segment |
| `ca` | Number of major vessels (0-3) colored by fluoroscopy |
| `thal` | Thalassemia type (0-3) |
| **Target (`output`)** | 1 = Heart Disease Present, 0 = No Heart Disease |

---
