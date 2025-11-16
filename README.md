# 🍕 Food Delivery Time Prediction Using Machine Learning

## 🎯 Project Objective
This project predicts **food delivery time (in minutes)** using machine learning by analysing factors like **distance, traffic, weather conditions**, and **delivery partner details**.  
The goal is to improve ETA accuracy for platforms such as **Zomato, Swiggy, and UberEats**.

---

## 📂 Dataset Information
The dataset contains detailed records of food deliveries, including:

- Delivery partner details  
- Restaurant & customer locations  
- Traffic & weather conditions  
- Order type and vehicle type  
- Number of deliveries in a trip  
- Time-based features (hour, day, peak hour, festival status)  
- **Actual delivery time (target variable)**  

---

## 🧠 Machine Learning Pipeline

### **1️⃣ Data Preprocessing**
- Handled missing values  
- Removed irrelevant ID columns  
- Encoded categorical variables  

### **2️⃣ Feature Engineering**
- Calculated **distance** using geolocation coordinates  
- Extracted **order hour** and **day of week**  
- Added **peak-hour** and **festival** indicators  

### **3️⃣ Exploratory Data Analysis (EDA)**
- Weather vs Delivery Time  
- Traffic vs Delivery Duration  
- Distance vs Delivery Time  
- Correlation Heatmap  

### **4️⃣ Model Building**
Algorithms used:
- **Linear Regression**  
- **Random Forest Regressor**

### **5️⃣ Evaluation Metrics**
- **MAE (Mean Absolute Error)**  
- **RMSE (Root Mean Squared Error)**  
- **R² Score**  

---

## 📊 Model Performance

| Model             | MAE | RMSE | R² Score |
|------------------|-----|------|---------|
| Linear Regression | 5.1 | 6.2  | 0.68    |
| **Random Forest** | **2.9** | **3.4** | **0.89** |

✔ **Best Model: Random Forest**  
✔ **Average Error ≈ 3 minutes**  

---

## 🔍 Key Insights
- Distance and traffic have the **strongest impact** on delivery duration  
- Peak hours & festival days cause **significant delays**  
- Random Forest performs better by handling **non-linear relationships**  

---

## 🛠️ Technologies Used
- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Scikit-Learn**  
- **Jupyter Notebook**

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook Food_Delivery_Model.ipynb
