# ML_Project
# Machine Learning Project – Clustering & Classification

## 📌 Project Overview

This project demonstrates the full **Machine Learning pipeline**, starting from raw (unclean) data, through **data preprocessing**, **model training**, **evaluation**, and **comparison of multiple algorithms**.
The project is implemented using **Jupyter Notebooks** and divided into two main parts:

1. **Clustering (Unsupervised Learning)**
2. **Classification (Supervised Learning)**

Each notebook focuses on proper preprocessing and the use of multiple models as required by the course project specifications.

---

## 📂 Project Structure

```
Machine_Learning_Project/
│
├── data/
│   ├── mall_customers.csv          # Clustering dataset
│   ├── credit_card_default.csv      # Classification dataset
│
├── notebooks/
│   ├── 1_Clustering.ipynb
│   ├── 2_Classification.ipynb
│
├── requirements.txt
├── README.md
```

---

## 📊 Datasets Description

### 1️⃣ Clustering Dataset (Customer Segmentation – Mall Customers)

* Source: [Kaggle – Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
* Type: Unsupervised dataset
* Size: ~5,000+ rows
* Features: Age, Gender, Annual Income, Spending Score, etc.
* Contains:

  * Missing values
  * Duplicates
  * Categorical features
  * Outliers
  * Unscaled numerical features

### 2️⃣ Classification Dataset (Credit Card Default – Taiwan)

* Source: [Kaggle – Default of Credit Card Clients Dataset](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset)
* Type: Binary classification
* Size: ~30,000 rows
* Target: Default Payment (0 = No, 1 = Yes)
* Contains:

  * Missing values
  * Categorical features
  * Imbalanced classes
  * Unscaled numerical features

---

## 🛠 Preprocessing Steps Applied

The following preprocessing techniques are applied in both notebooks (as applicable):

* Handling **Missing Values**
* Removing **Duplicate Rows**
* **Encoding** categorical variables
* **Feature Scaling** using Standardization / Normalization
* Handling **Class Imbalance** (SMOTE / undersampling if needed)
* **Outlier Detection & Treatment**
* Train-Test Splitting

---

## 🤖 Models Implemented

### ✅ Clustering Notebook

* **K-Means Clustering**
* **DBSCAN**

Evaluation Metrics:

* Silhouette Score
* Elbow Method
* PCA Visualization

---

### ✅ Classification Notebook

Two models are selected from the approved list:

* **Logistic Regression**
* **Naive Bayes / Decision Tree / Linear SVC** (one or more)

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC Curve & AUC

---

## 📈 Results & Comparison

Each notebook contains:

* Performance comparison between models
* Graphical visualizations of predictions
* Confusion matrices
* Discussion of the best-performing model

---

## 💻 Requirements

All required libraries are listed in `requirements.txt`. Main dependencies include:

* Python 3.9+
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Imbalanced-learn

To install requirements:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run the Project

1. Clone or download the project folder.
2. Install required libraries.
3. Open Jupyter Notebook.
4. Run notebooks in this order:

   * `1_Clustering.ipynb`
   * `2_Classification.ipynb`

---

## 🎯 Learning Outcomes

Through this project, we covered:

* End-to-end Machine Learning workflow
* Data cleaning and preprocessing techniques
* Unsupervised vs Supervised learning
* Model evaluation and comparison
* Working with imbalanced data

---

## 👥 Team Members

* [Student Name 1]
* [Student Name 2]
* [Student Name 3]
* [Course Name & University]

---

## 📜 License

This project is for academic and educational purposes only.

---

✅ This README follows standard academic ML project documentation format and is suitable for submission.
