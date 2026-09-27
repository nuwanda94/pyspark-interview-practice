# PySpark Interview Practice

**50+ carefully curated PySpark interview problems** with progressive difficulty and practical hints.

Designed for daily practice so you can build muscle memory for Data Engineer / Senior Data Engineer interviews.

---

## 🚀 Quick Start

1. Clone the repo
```bash
git clone https://github.com/nuwanda94/pyspark-interview-practice.git
cd pyspark-interview-practice
```

2. Open the notebook
```bash
jupyter notebook notebooks/pyspark_interview_practice.ipynb
```

Or use VS Code / Databricks / Google Colab (with Java + PySpark installed).

3. Create a SparkSession (already provided in the first cell) and start solving!

---

## 📚 What's Inside

| Section | # Problems | Focus |
|---------|------------|-------|
| 1. Basics & Spark Concepts | 8 | RDD vs DataFrame, Lazy Evaluation, Transformations/Actions |
| 2. DataFrame Operations | 10 | Select, Filter, Null handling, Duplicates, Schema |
| 3. Aggregations & GroupBy | 6 | groupBy, agg, pivot, collect_list |
| 4. Joins | 7 | All join types, Broadcast, Anti/Semi joins |
| 5. Window Functions | 10 | Ranking, Running totals, Lag/Lead, Top-N |
| 6. Performance & Optimization | 5 | Skew, Partitioning, Caching, AQE concepts |
| 7. Real Coding Scenarios | 10 | Deduplication, Consecutive events, Complex ETL patterns |

**Total: 56 problems**

---

## 🎯 How to Practice Daily

**Recommended routine (30–45 min/day):**

- **Day 1–3**: Sections 1–2 (Basics + DataFrame ops)
- **Day 4–6**: Aggregations + Joins
- **Day 7–10**: Window Functions (most important for interviews)
- **Day 11–14**: Performance concepts + Real scenarios
- **Ongoing**: Revisit hard problems + time yourself

**Rules for maximum benefit:**
1. Try solving **without looking at hints** first.
2. Only open the hint after 5–7 minutes of struggle.
3. Write the code yourself — do not copy-paste solutions.
4. After solving, think: *"What would the Spark UI look like? Any shuffle?"*

---

## 🛠️ Requirements

```bash
pip install pyspark jupyter
```

Java 8/11/17 is required for Spark.

---

## 📁 Repo Structure

```
pyspark-interview-practice/
├── README.md
├── notebooks/
│   └── pyspark_interview_practice.ipynb   # Main practice notebook (problems + hints)
└── solutions/                             # Optional self-check (add your own later)
```

---

## 💡 Tips from a Principal Data Engineer

- Interviewers care more about **why** you chose a certain approach (broadcast vs shuffle join, window vs groupBy) than perfect syntax.
- Always mention data volume assumptions when discussing performance.
- Practice explaining your solution out loud.

---

**Star ⭐ the repo if it helps you!**  
Feel free to open issues for more problems or corrections.

Happy practicing! 🔥
