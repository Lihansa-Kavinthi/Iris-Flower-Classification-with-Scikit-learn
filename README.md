# Iris Flower Classification 🌸

A machine learning project that classifies Iris flowers into three species (**Setosa**, **Versicolor**, and **Virginica**) based on sepal and petal measurements using Scikit-learn.

## 📌 Project Overview
This project serves as an introduction to **Supervised Machine Learning**. We use a labeled dataset to train a classification algorithm, evaluate its performance, and understand how features like petal width and length influence the model's decisions.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** * `pandas` (Data manipulation)
    * `scikit-learn` (Machine learning & preprocessing)
    * `matplotlib`/`seaborn` (Data visualization)

## 📊 Dataset
The dataset used is the [Iris CSV from Kaggle](https://www.kaggle.com/datasets/saurabh00007/iriscsv). It contains 150 instances of iris flowers with 4 features:
1. Sepal Length (cm)
2. Sepal Width (cm)
3. Petal Length (cm)
4. Petal Width (cm)

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone [https://github.com/your-username/iris-classification.git](https://github.com/your-username/iris-classification.git)
cd iris-classification
```
### 2. Install dependencies
Ensure you have Python installed, then run:

```bash
pip install pandas scikit-learn
```

### 3. Run the script

```bash
python iris_model.py
```
## 🧠 Machine Learning Workflow

1. **Data Loading:** Importing the CSV and inspecting the structure.
2. **Preprocessing:** Splitting the data into training (80%) and testing (20%) sets.
3. **Model Selection:** Implementing the **K-Nearest Neighbors (KNN)** algorithm.
4. **Training:** Fitting the model to the training data.
5. **Evaluation:** Measuring performance using accuracy scores and classification reports.

## 📈 Results

> **Model Accuracy:** The model typically achieves an accuracy of **95% - 100%** on the test set.

This high performance demonstrates the effectiveness of simple classification algorithms, like **KNN**, when applied to well-defined and chemically distinct datasets like the Iris flowers.

### Key Performance Indicators:
* **Precision:** High across all three classes, meaning few false positives.
* **Recall:** Excellent, particularly for the *Setosa* class, which is linearly separable from the others.
* **F1-Score:** Typically above 0.96, showing a strong balance between precision and recall.
