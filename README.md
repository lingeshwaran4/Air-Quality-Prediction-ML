# 🌍 Air Quality Prediction using Machine Learning

## 📌 Project Overview  
This project focuses on predicting Air Quality Index (AQI) using machine learning techniques.  
We implemented **regression** for continuous AQI values and **classification** to categorize air quality into predefined buckets such as *Good, Satisfactory, Poor, Very Poor, Severe*.  

---

🎥 **Presentation (PPTX)**: [View PPT](https://docs.google.com/presentation/d/18nMu6oXdZnBGCBwx7keWAVUtvaOAxCyO/edit?usp=sharing&ouid=101301702383994895963&rtpof=true&sd=true

---

## 📊 Dataset Details  
- **Dataset Name**: Air Quality Analysis of Delhi  
- **Source**: [Kaggle – Air Quality Analysis of Delhi](https://www.kaggle.com/code/yashvi/air-quality-analysis-of-delhi/input)  
- **File Format**: `.csv`  

### 📑 Dataset Description  
The dataset contains air quality measurements across Delhi, with features including:  
- **PM2.5 & PM10**: Particulate matter concentrations (in µg/m³)  
- **NO, NO₂, NOx**: Nitrogen oxide pollutants  
- **CO, SO₂, O₃**: Other gaseous pollutants  
- **Benzene, Toluene, Xylene**: Hazardous volatile compounds  
- **City / Station Name**: Location of measurement  
- **AQI**: Air Quality Index (target for regression)  
- **AQI_Bucket**: Categorized AQI levels (target for classification)  

---

## ⚙️ Tools & Technology Used  

| Category            | Tools / Libraries |
|---------------------|------------------|
| Programming         | Python (Jupyter Notebook) |
| Data Processing     | Pandas, NumPy |
| Visualization       | Matplotlib, Seaborn |
| Machine Learning    | Scikit-learn (Regression + Classification) |
| Model Evaluation    | MAE, R² Score, Accuracy |
| Version Control     | Git, GitHub |

---

## 🔬 Methodology  
1. **Data Cleaning** – Handle missing values, remove duplicates, fix formatting  
2. **Exploratory Data Analysis (EDA)** – Visualize pollutant levels and AQI distribution  
3. **Feature Engineering** – Encode categorical features, scale numerical data  
4. **Model Training** –  
   - Regression: Predict continuous AQI values  
   - Classification: Categorize AQI into buckets  
5. **Evaluation** –  
   - Regression: MAE, R²  
   - Classification: Accuracy, Confusion Matrix  
6. **Visualization** – Generate graphs for pollutant trends and prediction results  

---

## ❗ Problem Statement  
Air pollution is one of the most pressing urban challenges.  
Delhi consistently records hazardous AQI levels, which can severely impact human health.  
A reliable prediction system is needed to forecast air quality, enabling citizens and authorities to take proactive measures.  

---

## 💡 Solution  
We built an **ML-powered prediction model** that:  
- Predicts the AQI (numerical value) using regression models  
- Classifies air quality into categories (Good, Poor, Severe, etc.)  
- Visualizes pollution patterns to gain insights  
- Provides a foundation for deploying real-time AQI monitoring apps  

---

## 📈 Results  

📌 **Regression Results:**  
- **Mean Absolute Error (MAE):** `13.81`  
- **R² Score:** `94.93%`  

📌 **Classification Results:**  
- **Accuracy:** `83.01%`  

---

## 📂 Repository Structure  

Air-Quality-Prediction-ML/
│── AirQualityPrediction.ipynb # Jupyter Notebook (data cleaning, modeling, visualization)
│── results.txt # Saved output (metrics & predictions)
│── README.md # Project documentation
│── LICENSE # License file
│── requirements.txt # Dependencies
│── images/ # Visualizations (graphs, plots, charts)
│── data/ # Raw & processed datasets