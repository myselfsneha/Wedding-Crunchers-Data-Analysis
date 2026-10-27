<div align="center">

# WEDDING CRUNCHERS
### A closer look at the wedding budget.

*An exploratory data analysis project built with Python — with a little editorial-luxury energy.*

![Python](https://img.shields.io/badge/Python-702D3C?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-292321?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-C9A96E?style=flat-square&logo=numpy&logoColor=292321)
![Matplotlib](https://img.shields.io/badge/Matplotlib-7D8975?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-B9787D?style=flat-square)

</div>

---

## The idea

Wedding budgets bring together a lot of moving parts. This project explores how to inspect and visualise those numbers — from the cost breakdown to differences between city and season labels.

**One important note:** the current dataset contains **500 synthetic records generated in Python**. It is a learning dataset, not a collection of real wedding transactions. The charts are useful for practising analysis, but they cannot establish real wedding-market trends.

## Inside the notebook

| Chapter | What it explores |
| --- | --- |
| **Data check** | Sample size, missing values, duplicate IDs and summary statistics |
| **Budget breakdown** | Venue, catering, decor and photography costs |
| **Cost distribution** | Mean, median, range and overall budget spread |
| **Guest count** | A visual and correlation check against total cost |
| **City comparison** | Descriptive summaries by generated city label |
| **Season comparison** | Cost distribution across generated season labels |
| **Relationships** | Correlations between component costs and their calculated total |
| **Limitations** | What the sample can — and cannot — tell us |

## The visual direction

Warm paper tones, deep wine, muted rose and champagne accents give the notebook a more considered editorial feel. The goal is to make the charts easier to read without turning a data project into a wall of decoration.

## Stack

- **Python** — analysis workflow
- **Pandas & NumPy** — data generation, preparation and summaries
- **Matplotlib & Seaborn** — visual exploration
- **Jupyter Notebook** — documented, reproducible workflow

## Project files

```text
Wedding-Crunchers-Data-Analysis/
├── README.md
├── Wedding-Crunchers-Data-Analysis.ipynb
└── wedding_data.csv
```

The notebook writes `wedding_data.csv` to its current working directory when run.

## What comes next

A stronger next iteration would use a documented, permissioned real dataset. That would make it possible to test genuine cost drivers, compare locations more responsibly, and decide whether forecasting is appropriate. A prediction model is **not presented as a result yet** because the current synthetic data does not support a meaningful market forecast.

## About

**Sneha Singh**

- Portfolio: [myselfsneha.github.io/sneha-portfolio](https://myselfsneha.github.io/sneha-portfolio/)
- LinkedIn: [singh--sneha](https://www.linkedin.com/in/singh--sneha/)
- GitHub: [@myselfsneha](https://github.com/myselfsneha)

---

<sub>Made for learning, analysis and better data storytelling.</sub>
