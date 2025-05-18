
# 🧠 Support Vector Machine (SVM) – Iris Dataset Classification

This project demonstrates how to use a **Support Vector Machine (SVM)** classifier to perform binary classification on the **Iris dataset**, with a focus on understanding and visualizing **support vectors** and the decision boundary.

---

## 📌 Project Highlights

- ✔️ Binary classification: **Setosa vs Versicolor**
- ✔️ Uses `scikit-learn` for SVM with a **linear kernel**
- ✔️ Visualizes:
  - Decision boundary
  - Margins
  - Support vectors
- ✔️ Clean, well-commented Jupyter Notebook

---

## 📁 Dataset Information

- 📚 Dataset: [Iris Dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)
- 📊 Features:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- 🎯 Labels: 
  - `0` – Setosa  
  - `1` – Versicolor  
  *(Versicolor and Virginica are excluded for binary classification)*

---

## 🚀 Getting Started

### 🔧 Prerequisites

Install the required Python libraries using pip:

```bash
pip install numpy pandas matplotlib scikit-learn
````

### 📥 Clone this Repository

```bash
git clone https://github.com/your-username/svm-support-vectors-demo.git
cd svm-support-vectors-demo
```

---

## 📒 Jupyter Notebook Overview

### `SVM_Support_Vectors_Iris.ipynb`

This notebook covers:

1. **Data loading and preprocessing**
2. **Binary class conversion (Setosa vs Versicolor)**
3. **Feature scaling using `StandardScaler`**
4. **Model training with `SVC(kernel='linear')`**
5. **Visualization of decision boundary and support vectors**

---

## 📈 Output Example

![SVM Output](https://upload.wikimedia.org/wikipedia/commons/2/2a/SVM_margin.png)

---

## 🧠 What are Support Vectors?

Support vectors are **data points that lie closest to the decision boundary**. These points are the most critical elements of the dataset — removing them would alter the margin or decision boundary.

> SVM aims to **maximize the margin** between the classes by relying on these support vectors.

---

## 🏗️ Project Structure

```
svm-support-vectors-demo/
│
├── SVM_Support_Vectors_Iris.ipynb   # Main Jupyter Notebook
├── README.md                        # Project documentation
```
---

## ✨ Acknowledgements

* [Scikit-learn Documentation](https://scikit-learn.org/)
* [Iris Dataset Reference](https://archive.ics.uci.edu/ml/datasets/iris)

--
---

⭐ **If you found this useful, give it a star!**


