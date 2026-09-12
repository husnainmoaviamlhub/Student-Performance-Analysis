# 📊 Student Performance Analysis

A complete end-to-end data analysis project on the **Student Performance Dataset**, covering everything from data cleaning to statistics, probability, hypothesis testing, visualizations, linear algebra, and calculus (gradient descent) — all built from scratch in Python.

---

## 🔍 Overview

This project analyzes academic and behavioral data of 395 students to uncover what factors actually influence final grades (`G3`). It goes beyond basic EDA by connecting the findings to the underlying math (linear algebra & calculus) that powers most ML models.

## 🧠 What's Inside

- ✅ **Data Cleaning** — null checks, duplicate removal, structure inspection
- 📈 **8+ Visualizations** — histograms, count plots, box plots, scatter plots & pie charts, each with a one-line takeaway
- 🧪 **Hypothesis Testing** — statistically validated whether study time impacts pass rate (p = 0.031)
- ➗ **Linear Algebra** — vectors, matrices, transpose, dot product, vector norm, matrix multiplication (XᵀX)
- 📉 **Calculus** — derivatives, partial derivatives, gradients, and a from-scratch **Gradient Descent** implementation to fit a best-fit line
- 📝 **Final Conclusions** — key insights summarized in plain English

## 🛠️ Tech Stack

- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- SymPy

## 📌 Key Findings

- Dataset was clean — **395 rows, 33 columns**, no missing values or duplicates
- Average final grade: **~10.4/20** | Overall pass rate: **~67%**
- Students who study more pass at a noticeably higher rate (**75% vs 67%**) — confirmed statistically significant (p < 0.05)
- Past failures show a strong negative relationship with final grades
- Number of absences shows **no strong relationship** with final grade
- Gradient descent converged to the same best-fit line as the closed-form solution: `G3_hat = 3.67 * G1_normalized + 10.42`

## 🚀 How to Run

```bash
git clone https://github.com/<your-username>/student-performance-analysis.git
cd student-performance-analysis
pip install pandas numpy matplotlib seaborn sympy
jupyter notebook Student_Performance_Analysis.ipynb
```

## 📂 Dataset

Student Performance Dataset (UCI Machine Learning Repository) — includes demographic, social, and academic attributes of students along with their grades (G1, G2, G3).

## 🤝 Contributing

Suggestions and improvements are welcome — feel free to open an issue or a pull request.

## 📬 Contact

If you'd like to connect or discuss this project, feel free to reach out via LinkedIn.

---

⭐ If you found this project useful, consider giving it a star!
