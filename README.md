# 🧠 Patient Risk Classification & Dashboard 📊

This project classifies patients into Low, Medium, or High cardiovascular disease (CVD) risk levels using a machine learning model, and visualizes health insights through a Power BI dashboard.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `eda_model.py` | Python script for data preprocessing, EDA, and ML prediction |
| `dashboard_health.pbix` | Power BI dashboard file for visual insights |
| `patients_data.csv` | Dataset containing patient information from Bangladesh|

---

## 🛠️ Project Flow & Implementation

### 1. 📊 Data Understanding & Preprocessing
- The dataset includes age, gender, BMI, blood pressure, lifestyle habits, diabetes status, cholesterol, and more.
- Null values and outliers were handled during preprocessing.
- New columns were engineered:
  - BMI Category
  - Blood Pressure Category
  - Smoking Flag
  - Waist-to-Height Ratio

### 2. 🔍 Exploratory Data Analysis (EDA)
- EDA was performed using Python:
  - Distribution of age, BMI, blood pressure
  - Correlation between lifestyle and CVD risk
  - Impact of smoking and diabetes on risk

### 3. 🤖 Machine Learning
- A Random Forest classifier was trained using:
  - Features: Age, BMI, Diabetes, Smoking, BP, etc.
  - Target: Risk Level (Low, Medium, High)
- Predictions were appended to the dataset and saved for dashboard use

### 4. 📊 Power BI Dashboard
- Key insights and visualizations:
  - 💉 Risk level distribution by demographics
  - 🏃 Lifestyle impact on health risk
  - 📈 Blood Pressure & Cholesterol insights
  - 📌 Summary KPIs: % High Risk, Avg BMI, % Smokers, etc.

Navigation across pages is done using buttons and slicers for interactivity.

---

## 🚀 How to Use

1. Clone this repo or download files
2. Run `eda_model.py` in Python to generate predicted risk data
3. Open `dashboard_health.pbix` in Power BI Desktop
4. Refresh the dataset if needed
5. Explore the interactive insights

---


