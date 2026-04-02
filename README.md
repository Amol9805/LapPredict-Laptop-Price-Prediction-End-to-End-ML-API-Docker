# 💻 LapPredict: Laptop Price Prediction (End-to-End ML + Streamlit App)

## 📌 Project Overview
This project delivers an **end‑to‑end machine learning solution** to predict laptop prices based on specifications.  
It combines a robust ML pipeline with a **Streamlit web application**, enabling real‑time predictions and interactive insights.  

The solution helps **SmartTech Co.** make data‑driven pricing decisions, analyze brand influence, and estimate prices for new laptop configurations.

---

## 🎯 Business Objective
- Predict laptop prices accurately using hardware and brand features  
- Assist in competitive market pricing strategies  
- Analyze **brand impact** on pricing (e.g., Apple premium effect)  
- Provide **real‑time price estimation** via a Streamlit app  

---

## 📊 Dataset Details
- Format: CSV  
- Records: ~1300 laptops  
- Features: 13 columns  
- Target: Laptop Price  

Key features include:
- Brand  
- CPU type  
- RAM & Storage (HDD/SSD)  
- Screen resolution & PPI  
- Weight  
- Operating system  

---

## 🛠 Tech Stack
- **Language:** Python  
- **Framework:** Streamlit  
- **Environment:** Jupyter Notebook + Streamlit App  
- **Libraries:**  
  - pandas, numpy  
  - matplotlib, seaborn  
  - scikit‑learn  
  - XGBoost  
  - Streamlit  

---

## 🚀 Project Workflow
1. **Data Exploration**  
   - Identified key predictors (Brand, RAM, SSD, PPI)  
   - Observed skewness in price distribution  

2. **Preprocessing & Feature Engineering**  
   - Extracted **PPI** from resolution  
   - Encoded categorical variables  
   - Applied **log transformation** on price  

3. **Model Development**  
   - Linear Regression  
   - Random Forest Regressor  
   - Gradient Boosting Regressor  
   - XGBoost Regressor  

4. **Hyperparameter Tuning**  
   - Optimized depth, learning rate, estimators  

5. **Deployment**  
   - Built a **Streamlit app** for real‑time predictions  
   - Interactive UI for entering laptop specs  

---

## 📈 Key Insights
- **Brand strongly influences price** (Apple premium effect)  
- **RAM & SSD size** are major predictors  
- **Higher PPI** increases laptop value  
- Tree‑based models outperform linear regression  

---

## 🖥 Streamlit Application

### Features
- Input laptop specifications via interactive form  
- Get **instant price predictions**  
- Visualize feature importance and correlations  
- Explore dataset insights with charts  

### Run Locally
```bash
# Clone the repository
git clone https://github.com/Amol9805/LapPredict-Laptop-Price-Prediction-Streamlit-App.git
cd LapPredict-Laptop-Price-Prediction-Streamlit-App

# Install dependencies
pip install -r requirements.txt

# Launch Streamlit app
streamlit run app.py
