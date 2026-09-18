# CodeAlpha_IrisClassification 🌸

**Data Science Internship — CodeAlpha | Task 1: Iris Flower Classification**

## 📌 Project Overview
This project builds a machine learning model to classify Iris flowers into one of three species — *Setosa*, *Versicolor*, or *Virginica* — based on four measurements: sepal length, sepal width, petal length, and petal width.

## 📂 Repository Structure
```
CodeAlpha_IrisClassification/
├── data/
│   └── Iris.csv                # Dataset (150 samples, 3 classes)
├── plots/                      # Saved visualizations
│   ├── pairplot.png
│   ├── correlation_heatmap.png
│   ├── model_comparison.png
│   └── confusion_matrix.png
├── Iris_Classification.ipynb   # Main notebook (EDA + modeling + evaluation)
└── README.md
```

## 🛠 Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn (visualization)
- Scikit-learn (LabelEncoder, StandardScaler, train_test_split, LogisticRegression, KNN, Decision Tree, Random Forest, evaluation metrics)

## 🔍 Workflow
1. **Data Loading & Exploration** — inspected shape, types, class balance
2. **EDA** — pairplot and correlation heatmap to understand feature relationships
3. **Preprocessing** — label-encoded target, standardized features
4. **Modeling** — trained and compared 4 classifiers: Logistic Regression, KNN, Decision Tree, Random Forest
5. **Evaluation** — accuracy, confusion matrix, precision/recall/F1 via classification report

## 📊 Results
Best model achieved **~93% accuracy** on the held-out test set. Petal length and petal width were the most discriminative features — Setosa is linearly separable from the other two species, while Versicolor and Virginica show slight overlap.

## ▶️ How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook Iris_Classification.ipynb
```

## 🎓 Internship
This task was completed as part of the **CodeAlpha Data Science Internship**.
