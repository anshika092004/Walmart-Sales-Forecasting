# 🛒 Walmart Sales Forecasting

A machine learning project to forecast weekly sales across Walmart stores using historical data, with interactive insights visualized through Power BI.

---

## 📌 Problem Statement

Retail sales are influenced by a variety of factors such as seasonality, holidays, and markdowns. The objective of this project is to build a predictive model that estimates Walmart's weekly sales using historical data and visualize actionable insights through a Power BI dashboard.

---

## 🧰 Tools & Technologies Used

- **Python**: Data Cleaning, Feature Engineering, Modeling
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost
- **Machine Learning Models**: Random Forest, XGBRegressor
- **Visualization**: Power BI
- **Others**: Jupyter Notebook, Git

---

## 📂 Dataset

- **Source**: [Kaggle – Walmart Store Sales Forecasting](https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting/data)
- **Files Used**:
  - `train.csv`: Weekly sales data by store and department
  - `features.csv`: Additional data like temperature, fuel price, markdowns
  - `stores.csv`: Store types and sizes

---

## 🧪 Key Features & Steps

1. **Exploratory Data Analysis (EDA)**  
   - Trend analysis across time, store types, and holidays  
   - Outlier detection and handling missing values

2. **Feature Engineering**  
   - Extracted Year, Month, Week, DayOfWeek  
   - Created rolling averages and lag features  
   - Encoded holidays and markdown strategies

3. **Model Building**  
   - Trained regression models using Scikit-learn  
   - Evaluated using RMSE (Root Mean Squared Error)  
   - Hyperparameter tuning with learning rate and tree depth

4. **Power BI Dashboard**  
   - Sales trend by store, department, and holiday  
   - Interactive filters for year, month, store, and department  
   - Markdown effectiveness and KPIs

---
## 📈 Model Evaluation

Two models were trained and evaluated using Root Mean Squared Error (RMSE):

| Model           | RMSE     |
|----------------|----------|
| Random Forest  | **3010.15** |
| XGBoost        | **2769.42** ✅ *(Best)*

XGBoost provided better accuracy and was selected for the final predictions.

---

## 📊 Dashboard Preview

<img width="1280" height="718" alt="Screenshot 2025-07-28 213804" src="https://github.com/user-attachments/assets/eb841993-6a8a-4ff5-8da6-b3dfcae89dad" />

--- 

## 🔍 Results

- Achieved **RMSE**: 2769.42 with XGBoost
- Identified most impactful features: `IsHoliday`, `Store Type`, `Markdown1`, etc.
- Gained business insights like:
  - Sales spikes during Black Friday and Christmas
  - Certain departments consistently outperform others

---
## 📬 Contact

**Anshika Sharma**  
Aspiring Data Analyst | Passionate about turning data into insights

📧 [Email](mailto:anshikasharma9104@gmail.com) | 🌐 [GitHub](https://github.com/anshika092004) | 💼 [LinkedIn](https://www.linkedin.com/in/anshika-sharma-20376125a/)





