# Cookie Cats: Should We Move the Gate? An A/B Test Analysis

> **TL;DR**: [项目结论一句话——做完分析后回来填]

---

## 🎯 Problem & Objective

[在这里写你的 business context，2-3 段]

**Business question**: Should we move the first gate from level 30 to level 40 to improve player retention?

**Hypothesis**: Moving the first gate from level 30 to level 40 will improve player retention because players will have more time to develop engagement with the game before encountering a friction point.

---

## 📊 Key Findings

*This section will be populated after analysis is complete.*

---

## 🔬 Methodology

A rigorous end-to-end A/B testing workflow:

1. **Problem Framing & Hypothesis** — Defined H0/H1, primary/secondary/guardrail metrics
2. **Power Analysis** — Calculated required sample size given α=0.05, power=0.80, MDE=1pp
3. **Sanity Checks** — Sample Ratio Mismatch (SRM) test to validate randomization
4. **Statistical Testing** — Two-proportion z-test on retention metrics
5. **Segment Analysis** — Heterogeneous treatment effects by player behavior
6. **Practical vs Statistical Significance** — Evaluated business impact beyond p-values
7. **Business Recommendation** — Ship decision with reasoning

---

## 🛠 Tech Stack

- **Python**: pandas, numpy
- **Statistics**: statsmodels, scipy
- **Visualization**: matplotlib, seaborn
- **Environment**: Google Colab

---

## 📁 Repo Structure
cookie-cats-ab-test/
├── README.md
├── notebooks/
│   └── ab_test_analysis.ipynb    # Main analysis notebook
├── data/
│   └── cookie_cats.csv           # Raw dataset
└── images/                       # Generated charts

---

## 🚀 How to Run

Open `notebooks/ab_test_analysis.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook locally.

---

## 📝 Key Takeaways

*Reflections will be added after project completion.*

---

**Author**: Yidan Xiong
**Last updated**: May 2026
