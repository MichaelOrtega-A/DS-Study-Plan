# 🚢 Titanic Data Analysis Project

## 📊 Project Overview
This project explores and analyzes the Titanic dataset using Python and essential data science libraries. The primary goal is to clean, process, and analyze the dataset to uncover patterns related to passenger survival, focusing on factors like class, gender, embarkation port, and fare paid.

---

## 🔧 Technologies & Libraries Used

- Python 3.x
- Pandas – for data manipulation
- NumPy – for numerical operations
- Matplotlib & Seaborn – for visualizations
- Jupyter Notebook – for interactive analysis and presentation

---

## 📝 Key Steps:

1. **Data Cleaning & Preprocessing:**
   - Filled missing values (e.g., median age, mode for embarkation port).
   - Dropped unnecessary columns (Cabin, Ticket, PassengerId).
   - Converted appropriate columns to categorical types for optimization.
   - Engineered new features (e.g., extracted passenger titles, created family size).

2. **Exploratory Data Analysis (EDA):**
   - Calculated survival rates by passenger class and gender.
   - Identified youngest & oldest survivors (excluding infants).
   - Highlighted passengers who paid the highest fares.

3. **Pivot Table Analysis:**
   - Created a pivot table showing survival rates based on class & embarkation port.
   - Visualized pivot data using a heatmap for clearer interpretation.

4. **Visualization Comparison:**
   - Compared traditional `groupby()` output with pivot tables for readability.
   - Illustrated survival patterns using bar plots and heatmaps.

---

## 🔥 Key Findings:

- **Females had a significantly higher survival rate across all classes.**
- **First-class passengers had the highest chance of survival, regardless of embarkation port.**
- Survival chances were much lower for third-class males.
- The youngest survivor above 1 year old and the oldest survivor provide insights into evacuation priorities.

---

## 🚀 Next Steps:
Potential improvements:
- Build a machine learning model (e.g., logistic regression) to predict survival.
- Further analysis on additional engineered features (like title or family size).

---

## 🔧 How to Run:

1. Clone this repository.
2. Ensure you have Python and required libraries installed (`pandas`, `numpy`, `matplotlib`, `seaborn`).
3. Place the `train.csv` file in the same directory.
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Titanic_Analysis.ipynb
   ```
5. Run each cell sequentially to execute the analysis.

---

