# 🏡 Vancouver Housing Analysis

This project explores the relationship between **housing age** and **income disparities** across Metro Vancouver municipalities, based on data from the 2025 Housing Data Book.

## 🔍 Objective  
To investigate whether municipalities with older housing stocks experience lower household income or slower income growth, supporting insights for urban renewal and policy planning.

## 📁 Project Structure  

Data analysis of housing age and income disparities across Metro Vancouver municipalities (2025 Housing Data Book)

<pre> ```markdown ├── notebooks/ # Jupyter Notebooks (EDA & analysis) │ ├── 01_data_preparation.ipynb │ ├── 02_eda_univariate.ipynb │ └── 03_eda_multivariate.ipynb ├── raw/ # Original housing and income data (.xlsx) ├── processed/ # Cleaned & merged datasets (.pkl) └── README.md # Project overview ``` </pre>


## 📊 Key Findings
- Municipalities with **older housing** tend to show **lower income growth**.
- Areas with **moderately aged stock** dominate in the **middle-income** and **middle-growth** groups.
- High-growth municipalities are **absent from the oldest housing stock**, suggesting a potential link between **renewal and economic vitality**.

## ▶️ How to Run
1. Clone the repo  
2. Open the notebooks in sequence from `01_` to `03_`  
3. Ensure required libraries are installed (e.g., `pandas`, `matplotlib`, `seaborn`)

## 🧭 Next Steps
- Integrate variables such as **housing prices**, **tenure type**, or **built environment indicators**  
- Perform **geospatial mapping** (e.g., heatmaps by municipality)  
- Apply **clustering** or predictive modeling for deeper insights

