# Outlier Detection and Distribution Analysis (EDA)

This project focuses on analyzing the distribution of numerical features and detecting outliers in the California Housing dataset using visualization techniques and statistical methods.

---

## 📌 Project Overview

In this project:
- Loaded the California Housing dataset using sklearn
- Identified numerical features
- Visualized feature distributions using histograms
- Used boxplots to detect outliers
- Applied the IQR method to quantify outliers

---

## 🚀 Key Concepts

### 🔹 Distribution Analysis
- Histograms are used to understand the spread of data
- KDE (Kernel Density Estimation) helps visualize the probability distribution

---

### 🔹 Boxplots
- Visual tool to detect outliers
- Shows median, quartiles, and extreme values

---

### 🔹 Outlier Detection (IQR Method)

- Q1 = 25th percentile  
- Q3 = 75th percentile  
- IQR = Q3 - Q1  

Outliers are defined as:

Lower Bound = Q1 - 1.5 × IQR  
Upper Bound = Q3 + 1.5 × IQR  

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Workflow

1. Loaded dataset using `fetch_california_housing`
2. Selected numerical features
3. Plotted:
   - Histograms with KDE
   - Boxplots
4. Calculated IQR for each feature
5. Identified number of outliers per feature
6. Displayed dataset summary statistics

---

## Key Observations

- Some features show skewed distributions
- Boxplots clearly highlight extreme values
- Outliers vary across different features
- Distribution analysis helps understand data behavior before modeling

---

🔮 Future Improvements
Remove or treat outliers and compare results
Apply Z-score method for comparison
Integrate with feature scaling and modeling
Use real-world datasets

👩‍💻 Author
Shreya G
``` id="p4y1rm"
git clone https://github.com/yourusername/outlier-analysis-ml.git
