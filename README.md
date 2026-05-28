# 🎓 Student Performance Analysis & Prediction

> An end-to-end data science project analysing student exam scores across math, reading, and writing — with EDA, feature engineering, and ML models to predict average score and letter grade.

**Author:** Shreya Mishra | BIT Mesra, Jaipur
**Period:** Feb 2025 – Apr 2025

---

## ✨ Features

- **Exploratory Data Analysis** — grade distribution, gender comparison, test prep impact, score correlation heatmap
- **Feature engineering** — label encoding of categorical variables (gender, parental education, lunch type, test prep)
- **Linear Regression** — predicts a student's average score; evaluated with Mean Absolute Error (MAE)
- **Decision Tree Classifier** — predicts letter grade (A/B/C/D/F) with depth-5 tree; evaluated with accuracy and classification report
- **Key insights** — quantifies the effect of test preparation, parental education level, and lunch type on performance
- **Chart exports** — saves `student_eda.png` with all EDA plots

---

## 📂 Project Structure

```
student-performance-analysis/
│
├── student_performance_analysis.ipynb   # Main notebook
├── student_eda.png                      # EDA visualisation (generated on run)
└── README.md
```

---

## 🚀 Getting Started

**Clone the repo:**
```bash
git clone https://github.com/your-username/student-performance-analysis.git
cd student-performance-analysis
```

**Install dependencies:**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

**Run the notebook:**
```bash
jupyter notebook student_performance_analysis.ipynb
```

> 💡 The notebook generates 1,000 synthetic student records automatically. To use your own data, replace the data generation cell with `data = pd.read_csv('students.csv')`.

---

## 📊 Analysis Pipeline

```
Raw Data
   │
   ├── EDA ──► Grade distribution, gender boxplots,
   │           test prep bar chart, correlation heatmap
   │
   ├── Feature Engineering ──► Label encoding of categorical columns
   │
   ├── Linear Regression ──► Predict avg_score  (metric: MAE)
   │
   └── Decision Tree ──► Predict grade A/B/C/D/F  (metric: Accuracy)
```

---

## 🔍 Dataset Features

| Column | Type | Description |
|---|---|---|
| `gender` | Categorical | Male / Female |
| `parental_education` | Categorical | High school → Master's degree |
| `lunch` | Categorical | Standard / Free or reduced |
| `test_prep` | Categorical | Completed / None |
| `math_score` | Numeric | Score out of 100 |
| `reading_score` | Numeric | Score out of 100 |
| `writing_score` | Numeric | Score out of 100 |
| `avg_score` | Numeric | Mean of three scores *(derived)* |
| `grade` | Categorical | A / B / C / D / F *(derived)* |

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| Pandas | Data loading, wrangling, groupby analysis |
| NumPy | Numerical operations, synthetic data generation |
| Matplotlib & Seaborn | EDA visualisation and chart export |
| scikit-learn | Label encoding, train/test split, ML models, metrics |

**Environment:** Python 3.10 · Jupyter Notebook / Google Colab

---

## 👩‍💻 Author

**Shreya Mishra** — BIT Mesra, Jaipur

---

## 📄 License

For academic and portfolio purposes.
