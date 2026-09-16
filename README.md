# 🎬 Movie Correlation Analysis with Python

## 📋 Project Overview
This project explores a movie dataset using Python to discover what variables have the highest correlation with a movie's **gross earnings**. By leveraging data cleaning, scatter plots, regression visualizations, and correlation matrices, this analysis tests various hypotheses regarding budget, votes, company influence, and revenue.

---

## 🛠️ Tech Stack & Libraries Used
* **Programming Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn (`regplot`, correlation heatmaps)

---

## 🔍 Key Findings & Insights
1. **Budget vs. Gross Earnings:** There is a **high positive correlation (0.74)** between a film's budget and its gross earnings. My initial hypothesis that higher budgets drive higher returns proved correct.
2. **Votes vs. Gross Earnings:** **Votes** also display a strong positive correlation (**0.61**) with gross earnings, showing that audience engagement and popularity strongly scale with box office revenue.
3. **Company Correlation:** Interestingly, company size/identity showed a surprisingly low direct correlation to high gross earnings compared to budget and votes, initially proving my secondary assumption wrong.

---

## 📁 File Structure
* [`Movie Correlation Project.ipynb`](./Movie%20Correlation%20Project.ipynb) — Jupyter Notebook containing the full end-to-end Python code, visualizations, and data exploration steps.

---

## 🚀 How to Run the Project
1. Clone or download this repository.
2. Ensure you have Jupyter Notebook along with Pandas, Seaborn, and Matplotlib installed.
3. Update the file path in the notebook to point to your local `movies.csv` dataset and run the cells sequentially.
