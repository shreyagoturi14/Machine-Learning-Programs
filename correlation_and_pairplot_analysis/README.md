# Correlation and Pairplot Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on the California Housing dataset using correlation heatmaps and pair plots.

The goal is to understand relationships between features and identify patterns that can help in building better Machine Learning models.

---

## Project Overview

In this project:
- Loaded the California Housing dataset using sklearn
- Computed correlation between features
- Visualized relationships using:
  - Heatmap
  - Pairplot

---

## 🚀 Key Concepts

### 🔹 Correlation Matrix
- Shows the relationship between numerical features
- Values range from -1 to +1
  - **+1** → Strong positive correlation
  - **-1** → Strong negative correlation
  - **0** → No correlation

---

### 🔹 Heatmap Visualization
- Used to visualize correlation matrix
- Helps quickly identify highly related features

---

### 🔹 Pairplot
- Displays pairwise relationships between features
- Includes scatter plots and distributions
- Useful for detecting patterns and trends

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
2. Created DataFrame
3. Calculated correlation matrix
4. Visualized using heatmap
5. Generated pairplot for feature relationships

---

## 📊 Key Observations

- Some features show strong correlation with the target variable
- Pairplots help visualize linear and non-linear relationships
- Heatmaps make it easy to identify important features

---

🔮 Future Improvements
Perform feature selection based on correlation
Apply regression models on selected features
Compare model performance
Extend analysis to real-world datasets

👩‍💻 Author
Shreya G
