# 🍽️ Zomato Bangalore Data Analysis Project
![Zomato-Logo](https://github.com/user-attachments/assets/88076721-9767-4334-b143-7aa7f8ac1f0b)

This project focuses on analyzing Zomato restaurant data from Bangalore through data preprocessing, exploration, and insightful visualizations. The goal is to clean the data, understand key patterns, and present meaningful stories using interactive and aesthetic visualizations.

---

## 📁 Project Structure

```
├── zomato.csv                  # Original dataset
├── zomato_analysis.ipynb       # Full Jupyter/Colab notebook with code and visualizations
```

---

## 🧹 Data Preprocessing & EDA

### ✅ Objectives

* Clean raw Zomato data
* Handle missing, duplicate, and inconsistent values
* Convert data types (e.g., ratings and cost)
* Feature selection for analysis
* Generate summary statistics and basic insights

### 🔧 Preprocessing Steps

* Removed invalid and redundant entries (e.g., "NEW", "-" in ratings)
* Converted strings like "4.1/5" to numeric values
* Removed commas and converted "approx\_cost(for two people)" to numeric
* Handled missing values using `NaN` treatment
* Checked for duplicates and dropped them

### 📊 Exploratory Data Analysis

* Summary statistics (mean, median, mode)
* Value counts for categorical columns
* Distribution of ratings, votes, and restaurant types
* Correlation matrix to understand numeric relationships

---

## 📈 Data Visualization & Interpretation

### ✅ Objectives

* Build clear and aesthetically pleasing visualizations
* Use appropriate chart types to highlight key insights
* Add interactivity where applicable
* Interpret trends and patterns effectively

### 📊 Key Visualizations

| Visualization           | Description                                          |
| ----------------------- | ---------------------------------------------------- |
| **Pie Chart**           | Online order availability                            |
| **Bar Graph**           | Restaurants by location                              |
| **Histogram**           | Distribution of ratings                              |
| **Scatter Plot**        | Votes vs. Ratings with cost as size                  |
| **Heatmap**             | Correlation between numeric features                 |
| **Interactive Heatmap** | Zoomable & hoverable correlation matrix using Plotly |

### 🧠 Interpretation & Storytelling

* Areas with the highest number of restaurants
* Most common rating ranges and outlier detection
* How cost correlates with rating and votes
* Insights into consumer behavior for online orders

---

## 📜 Summary of Tools Used

* **Pandas & NumPy** – Data cleaning and manipulation
* **Matplotlib & Seaborn** – Static visualizations
* **Plotly Express** – Interactive graphs
* **Google Colab** – Notebook environment

---

## 🔗 How to Run the Project

1. Clone the repository or download it as a ZIP
2. Open `zomato_analysis.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook
3. Run all cells in order to reproduce the full analysis and visualizations

---

