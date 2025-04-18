# PRODIGY_DS_03
![Uploading image.png…]()


# 🤖 Bank Marketing Prediction using Decision Tree Classifier

This project builds a **Decision Tree Classifier** to predict whether a client will subscribe to a term deposit based on demographic and behavioral attributes using the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

---

## 📁 Dataset

- **Source**: [UCI Machine Learning Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- **File**: `bank-full.csv`
- **Target Variable**: `y` (yes/no – whether the client subscribed to a term deposit)

---

## 📌 Objective

To train a machine learning model that can **predict customer purchasing behavior** using a Decision Tree, and evaluate its performance using accuracy, classification metrics, and visualization.

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

---

## 🚀 Steps Performed

### 1. Data Loading & Inspection
- Loaded dataset using `pandas`
- Checked for null/missing values
- Reviewed data structure and summary statistics

### 2. Data Preprocessing
- Encoded categorical variables using `LabelEncoder`
- Split data into features (`X`) and target (`y`)
- Split dataset into training and testing sets (80/20)

### 3. Model Building
- Trained a **Decision Tree Classifier** (`max_depth=5`)
- Evaluated using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

### 4. Visualization
- Visualized the decision tree using `plot_tree` from `sklearn`

---

## 📊 Model Evaluation

The model provides an overview of which features contribute most to the prediction of customer conversion. It achieves reasonable performance, and serves as a baseline for future model improvements (e.g., Random Forest, GridSearchCV tuning, etc.)

---

## 📂 Files

- `Task3PT.ipynb` – Jupyter Notebook with full code and analysis
- `README.md` – Project documentation
- `bank-full.csv` – Dataset (not included here; download from [UCI link](https://archive.ics.uci.edu/ml/machine-learning-databases/00222/bank.zip))

---

