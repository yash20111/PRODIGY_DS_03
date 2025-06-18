# PRODIGY_DS_03
# 🧠 Decision Tree Classifier – Bank Marketing Prediction

This project builds a Decision Tree model to predict whether a client will subscribe to a term deposit, using demographic and behavioral data from the UCI Bank Marketing dataset.

## 📁 Dataset
- Source: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- File used: `bank-additional-full.csv`
- Target: `y` (`yes` = subscribed, `no` = not subscribed)

## 🔧 Features
- Label encoding of categorical variables
- Train-test split (80/20)
- Decision Tree training (depth = 5)
- Accuracy and classification report
- Full decision tree visualization

## 📈 Model Performance
- **Accuracy:** ~91.5%
- **Class-wise F1 Score:**
  - `No`: 0.95
  - `Yes`: 0.59 (can be improved with sampling techniques)

## 🔍 How to Run
1. Place `bank-additional-full.csv` in your project directory
2. Open and run the notebook: `decision_tree_classifier.ipynb`

## 📦 Requirements
```bash
pip install pandas matplotlib seaborn scikit-learn
