# OIBSIP — Data Science Internship

**Oasis Infobyte (AICTE OIBSIP) — Data Science Domain**
**Intern:** Sadan Mahankali

This repository contains my submissions for the Oasis Infobyte Data Science internship.
Each task is a self-contained project with its own dataset, reproducible notebook, a
runnable Python script, saved model artifacts, and a dedicated README explaining the
problem, approach, and results.

---

## 📌 Tasks

| # | Project | Type | Status |
|---|---------|------|--------|
| 1 | [Iris Flower Classification](./Task1_IrisFlowerClassification) | Supervised classification | ✅ Complete |
| 2 | Unemployment Analysis with Python | EDA / time series | ⏳ Planned |
| 3 | Car Price Prediction | Regression | ⏳ Planned |
| 4 | Email Spam Detection | NLP / classification | ⏳ Planned |
| 5 | Sales Prediction | Regression | ⏳ Planned |

---

## 🛠️ Tech stack

Python 3.13 · pandas · NumPy · scikit-learn · Matplotlib · seaborn · Jupyter

## ⚙️ Setup

```bash
git clone https://github.com/<your-username>/OIBSIP.git
cd OIBSIP
pip install -r requirements.txt
```

Each task folder contains:

```
TaskN_ProjectName/
├── README.md                     # problem, approach, results
├── SadanMahankali_TaskN.ipynb    # narrated analysis notebook
├── <project>.py                  # runnable script version
├── data/                         # dataset
├── models/                       # saved model artifact(s)
└── outputs/                      # generated figures
```

## ▶️ Running a task

```bash
cd Task1_IrisFlowerClassification
python iris_classification.py          # runs end-to-end, saves model + figures
# or open the notebook:
jupyter notebook SadanMahankali_Task1.ipynb
```

---

*Submitted as part of the Oasis Infobyte Internship Program.*
