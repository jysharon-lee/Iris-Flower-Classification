# Iris Flower Classification

> Part of the **ML/DL for Beginners** series — a step-by-step path for people getting into Machine Learning and Deep Learning, with zero prior ML experience assumed.
> ➡️ Next project: [Titanic Survival Prediction](#) — handling missing data & feature engineering

This is **Project 1** in the series — the classic "Hello World" of machine learning.

## 🎯 What You'll Learn

- The basic workflow of a supervised machine learning project, start to finish
- How to explore and visualize a dataset before touching any modeling code
- How a simple classification model (K-Nearest Neighbors) actually makes predictions
- How to evaluate a classifier using accuracy and a confusion matrix

## 📋 Prerequisites

- Basic Python (variables, loops, functions)
- No prior ML experience needed — this is designed to be your first ML project

## 📊 Dataset

**Name:** Iris Flower Dataset
**Source:** Built into scikit-learn (`sklearn.datasets.load_iris`) — no download needed
**Description:** 150 flower samples across 3 species (Setosa, Versicolor, Virginica), with 4 measurements per flower (sepal length/width, petal length/width). The goal is to predict the species from the measurements.

Because this dataset is built into scikit-learn, there's nothing to download — it loads directly in the notebook. This is intentional: Project 1 removes the extra step of dataset-wrangling so you can focus entirely on the ML workflow.

## 🛠️ Setup

```bash
# Clone this repo
git clone [repo-url]
cd iris-flower-classification

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook notebook.ipynb
```

## 📖 Steps Overview

1. **Introduction** — what we're predicting and why this dataset is the classic starting point
2. **Import libraries** — pandas, scikit-learn, matplotlib/seaborn, what each one does
3. **Load & explore the data** — first look at the data, summary statistics, visualizing the 3 species
4. **Data cleaning** — a quick check (this dataset is already clean — you'll learn *why* checking still matters)
5. **Train/test split** — why we never train and test on the same data
6. **Model building** — training a K-Nearest Neighbors classifier, explained step by step
7. **Model evaluation** — accuracy score and confusion matrix, explained in plain language
8. **Conclusion** — what we learned and what to try next

## ✅ Expected Results

By the end of the notebook, you should get roughly **95-100% accuracy** — this dataset is small and clean, so a high score here is expected, not a sign you've done something advanced.

## 🚀 Next Steps / Challenges

- [ ] Try changing `k` (the number of neighbors) in KNN — how does accuracy change with k=1 vs k=15?
- [ ] Try a different algorithm (Logistic Regression or Decision Tree) — compare its accuracy to KNN
- [ ] Try removing one of the 4 features — does accuracy drop? Which feature matters most?

## 📚 Further Reading

- Google's Machine Learning Crash Course — classification module (for the concepts used here)

## 📄 License

MIT — feel free to use this for your own learning.
