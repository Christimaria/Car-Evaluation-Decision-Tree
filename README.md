
# 🚗 Car Evaluation using Decision Tree Classification

## 📌 Project Overview

This project builds a **Decision Tree Classification** model to predict the **acceptability of a car** based on its characteristics. The project demonstrates a complete machine learning workflow, including data exploration, preprocessing, model training, evaluation, interpretation, and experimentation.

---

## 🎯 Objectives

* Explore and understand the Car Evaluation dataset.
* Perform Exploratory Data Analysis (EDA).
* Encode categorical features using Ordinal Encoding.
* Train a Decision Tree classifier.
* Evaluate the model using multiple performance metrics.
* Interpret the model using Feature Importance and Decision Tree visualization.
* Compare different tree depths and splitting criteria.

---

## 📂 Dataset

The dataset contains information about cars based on the following features:

* Buying Price
* Maintenance Cost
* Number of Doors
* Seating Capacity
* Luggage Boot Size
* Safety

**Target Variable**

* Car Acceptability (`unacc`, `acc`, `good`, `vgood`)

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Category Encoders
* Graphviz
* Jupyter Notebook

---

## ⚙️ Machine Learning Workflow

1. Data Loading
2. Exploratory Data Analysis
3. Data Preprocessing
4. Ordinal Encoding
5. Train-Test Split
6. Decision Tree Classification
7. Model Evaluation
8. Feature Importance Analysis
9. Decision Tree Visualization
10. Hyperparameter Experimentation

---

## 📊 Model Performance

* **Algorithm:** Decision Tree Classifier
* **Criterion:** Gini Index
* **Accuracy:** **94.41%**

The model performed well across all classes, with particularly strong performance on the **`unacc`** category.

---

## 🔍 Key Insights

* The dataset contained **no missing values** and **no duplicate records**.
* All features were categorical and encoded using **Ordinal Encoding**.
* **Persons** and **Safety** were identified as the most influential features.
* The model achieved high classification accuracy while maintaining good precision and recall.
* Increasing the tree depth improved accuracy, with the unrestricted tree producing the best result on the test set.

---

## 📁 Repository Structure

```text
Car-Evaluation-Decision-Tree/
│
├── Decision_Tree.ipynb
├── README.md
├── requirements.txt
├── dataset/
├── images/
└── LICENSE
```

---

## 🚀 Future Improvements

* Hyperparameter tuning using GridSearchCV
* Cross-validation
* Random Forest comparison
* Gradient Boosting comparison
* Handling class imbalance techniques

---

## 👤 Author

**Christi MB**

B.Tech Computer Science Engineering Student

Passionate about Machine Learning, Data Science, and Software Development.
