# 🍽️ Zomato Data Analysis – Bangalore

This project analyzes Zomato's Bangalore restaurant data to uncover insights through data preprocessing, cleaning, transformation, and visualization.

---

## 📌 Objective

To clean and analyze the Zomato dataset by:
- Handling missing and duplicate values
- Transforming and encoding features
- Visualizing trends, patterns, and outliers
- Summarizing key insights for business decisions

---

## 📁 Files

- `zomato_analysis.ipynb` – Main analysis notebook
- `zomato.csv` – Dataset (CSV format)
- `README.md` – Project summary

---

## ⚙️ Setup & Run

### Requirements
```bash
pip install pandas numpy matplotlib seaborn openpyxl
````

### Run the Project

**In Google Colab:**

1. Open Colab: [https://colab.research.google.com](https://colab.research.google.com)
2. Upload `zomato_analysis.ipynb` and `zomato.csv`
3. Run all cells

**In Jupyter Notebook:**

```bash
jupyter notebook zomato_analysis.ipynb
```

---

## 📊 Key Steps

* Cleaned `rate`, `cost`, and categorical columns
* Handled nulls with mode or dropped rows
* Encoded binary features (`online_order`, `book_table`)
* Removed duplicates and filtered outliers
* Visualized rating vs. cost, popular cuisines, and locations

---

## 🔍 Insights

* Online ordering is offered by most high-rated restaurants
* Locations like Indiranagar & Koramangala dominate quality food offerings
* North Indian and Chinese are top cuisines
* Votes positively correlate with rating

---
