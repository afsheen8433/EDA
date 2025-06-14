# Exploratory Data Analysis
# 🍷 Wine Quality EDA

This project performs **Exploratory Data Analysis (EDA)** on the [Wine Quality dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009), focusing on understanding the relationships between physicochemical properties of wine and its quality rating.

---

## 📁 Dataset

- **Source**: UCI Machine Learning Repository / Kaggle  
- **File**: `WineQT.csv`  
- **Records**: 1143  
- **Features**: 12 input variables + 1 target variable (`quality`)

---

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy)
- Data Visualization: Matplotlib, Seaborn
- Google Colab 

---

## 📊 Key EDA Steps

### ✅ Data Overview
- Checked shape, data types, missing values, and duplicates
- Dataset is clean and ready to use

### 📈 Univariate Analysis
- Histograms plotted for all numerical features
- Distribution of wine quality ratings analyzed

### 📦 Outlier Detection
- Boxplots used to visualize and detect outliers
- Notable outliers in `residual sugar`, `chlorides`, `sulphates`, and `total sulfur dioxide`

### 🔥 Correlation Analysis
- Heatmap shows:
  - **Positive correlation** between `alcohol` and `quality`
  - **Negative correlation** between `volatile acidity`, `total sulfur dioxide` and `quality`

---

## 📌 Insights

- **Alcohol content** is a strong positive predictor of wine quality
- Higher levels of **volatile acidity** and **sulfur dioxide** often indicate lower quality
- Features are moderately correlated, suitable for ML modeling

---

## 📂 Files Included

- `EDA(COLAB).ipynb`: Full EDA notebook with visualizations
- `WineQT.csv`: Dataset file

---

## 🚀 Future Work

- Data preprocessing and feature engineering
- Modeling with classification/regression algorithms
- Model evaluation and tuning

---

## 📬 Contact

Feel free to reach out if you have questions or suggestions!

> 📧 afsheen8433ansari@gmail.com 
> 💼 linkedin.com/in/afsheenansari  
> 🐙 github.com/afsheen8433 

---

## ⭐️ If you find this useful, don't forget to star the repo!
