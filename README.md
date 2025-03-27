# 🚗💰 Car Price Prediction  

Welcome to the **Car Price Prediction** project! This project predicts the price of a car based on various attributes using **Machine Learning**. If you're interested in understanding how data and algorithms help estimate car prices, this project is for you!  

---

## 📌 Project Overview  
This project utilizes historical car data, processes it, and applies a **Machine Learning Model** to predict car prices. It can help car buyers, sellers, and dealerships estimate a car's value before making a deal.  

---

## 🔥 Features  
- Predicts car prices based on **key attributes** (brand, model, year, mileage, etc.).  
- Uses **Machine Learning** for accurate predictions.  
- Performs **Exploratory Data Analysis (EDA)** to visualize trends.  
- Implements multiple ML models to determine the best-performing one.  

---

## 🛠️ Tech Stack  
- **Python** 🐍  
- **Jupyter Notebook** 📒  
- **Pandas, NumPy** (Data Processing)  
- **Matplotlib, Seaborn** (Data Visualization)  
- **Scikit-Learn, XGBoost** (Machine Learning)  

---

## 📂 Dataset Information  
The dataset includes key attributes that influence car pricing:  

| Feature         | Description |
|----------------|------------|
| `name`         | Car model |
| `year`         | Year of manufacture |
| `selling_price`| Selling price in INR |
| `km_driven`    | Total kilometers driven |
| `fuel`         | Fuel type (Petrol/Diesel/CNG/Electric) |
| `seller_type`  | Type of seller (Dealer/Individual) |
| `transmission` | Transmission type (Manual/Automatic) |
| `owner`        | Number of previous owners |
| `mileage`, `engine`, `max_power`, `seats` | Car specifications |

📌 **Dataset Source:** https://www.kaggle.com/datasets/slavapasedko/belarus-used-cars-prices  

---

## 🖼️ Project Workflow  

### 1️⃣ Data Collection & Preprocessing  
- Load and clean the dataset.  
- Handle missing values and outliers.  
- Convert categorical values into numerical ones.  


---

### 2️⃣ Exploratory Data Analysis (EDA)  
- Visualize data distributions, correlations, and patterns.  
- Analyze the relationship between **car attributes** and **price**.  


---

### 3️⃣ Model Training & Evaluation  
- Train multiple **Machine Learning models** (Linear Regression, Decision Tree, Random Forest, XGBoost).  
- Evaluate models using **R² Score, MAE, MSE, and RMSE**.  
- Identify the best-performing model for car price prediction.  

---

## 📊 Model Performance Summary  
🏆 **Best Model Selection Based on Performance Metrics**  

| Model | R² Score (Higher is Better) | MAE (Lower is Better) | MSE (Lower is Better) | RMSE (Lower is Better) |
|---|---|---|---|---|
| **Decision Tree Regressor** | 0.8530 | 1414.28 | 4,704,555.78 | 2,169.00 |
| **Random Forest Regressor** | 0.8841 ✅ | 1235.15 ✅ | 3,710,451.47 ✅ | 1,926.25 ✅ |
| **XGBoost Regressor** | **0.8883 ✅** | **1226.00 ✅** | **3,575,182.77 ✅** | **1,890.82 ✅** |
| **Linear Regression** | 0.8316 | 1563.71 | 5,388,411.90 | 2,321.30 |

📌 **Best Model Selection**  
- **XGBoost Regressor** is the best model as it has:  
  - ✅ The **highest R² Score (0.8883)** → Best at explaining price variations.  
  - ✅ The **lowest MAE (1226.00)** → Most accurate on average.  
  - ✅ The **lowest MSE (3,575,182.77) & RMSE (1,890.82)** → Least prediction error.  

---

## 🚀 How to Use  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/SandipVermaDev/Car-Price-Prediction.git
cd Car-Price-Prediction
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook
```bash
jupyter notebook
```
Open `Car Price Prediction.ipynb` and follow the steps inside!

---

## 📌 Results
- The model successfully predicts car prices with reasonable accuracy.
- Helps users make **data-driven** decisions when buying or selling cars.
- Further improvements can be made by adding more features or using advanced ML models.

---

## 📢 Contributing
Feel free to **fork** this repo, **improve** the model, and create a **pull request**! 🚀

---

## 📩 Contact
If you have any questions, feel free to reach out:
🔗 LinkedIn: [Sandip Verma](https://github.com/SandipVermaDev)

---

### ⭐ If you like this project, don't forget to give it a star! ⭐

