# 🧠 K-Nearest Neighbors (KNN) Classification

## 📌 Project Overview
This project implements a **K-Nearest Neighbors (KNN)** machine learning algorithm to classify breast cancer tumors as **Malignant (M) or Benign (B)** using the Breast Cancer Wisconsin dataset. It includes data analysis, preprocessing, feature scaling, model training, prediction, and performance evaluation.

## 🎯 Objectives
- Understand and implement the KNN classification algorithm.
- Perform exploratory data analysis (EDA).
- Identify missing values and analyze dataset features.
- Apply feature scaling using StandardScaler.
- Train and evaluate the KNN classification model.
- Compare model performance using different K values.

## 📂 Dataset Information
- **Dataset:** KNNAlgorithmDataset.csv
- **Problem Type:** Binary Classification
- **Target Column:** `diagnosis`
- **M:** Malignant
- **B:** Benign
- **Features:** Numerical tumor characteristics.

## 🛠️ Technologies & Libraries Used
- Python 🐍
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## ⚙️ Project Workflow

1. Import required libraries.
2. Load the breast cancer dataset.
3. Perform dataset exploration.
4. Check missing values.
5. Analyze target variable distribution.
6. Visualize numerical features using histograms.
7. Generate correlation heatmap.
8. Separate input features and target variable.
9. Split data into training and testing sets.
10. Apply StandardScaler for feature scaling.
11. Build the KNN classification model.
12. Train the model using `fit()`.
13. Predict using `predict()`.
14. Evaluate model performance.
15. Compare different K values (3, 5, 7, 9).

## 🤖 Machine Learning Algorithm

**K-Nearest Neighbors (KNN)**

- Algorithm Type: Supervised Learning
- Learning Method: Instance-Based Learning
- Model: `KNeighborsClassifier`
- Number of Neighbors: K = 5
- Distance Metric: Minkowski (default)

## 📊 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- Specificity
- Classification Error
- Training Accuracy
- Testing Accuracy

## 📈 Visualization
The project includes:
- Diagnosis Distribution Bar Chart
- Numerical Feature Histograms
- Correlation Heatmap
- Confusion Matrix Heatmap

## 📁 Project Structure

```text
KNN-Classification/
│
├── KNNAlgorithmDataset.csv
├── k-nearest-neighbors-knn.ipynb
└── README.md
```

## 🚀 How to Run the Project

1. Clone this repository:

```bash
git clone YOUR_REPOSITORY_URL
```

2. Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

3. Update the dataset path according to your system.

4. Run the Jupyter Notebook or Python file.

## 💡 Key Learning Outcomes
- Understanding KNN classification.
- Data preprocessing and feature scaling.
- Exploratory Data Analysis.
- Model building and prediction.
- Evaluating classification performance.
- Comparing different K values.

## 👨‍💻 Author

**Nawaz Shareef Shaik**

GitHub: https://github.com/ShaikNawazShareef

Machine Learning | Python | Artificial Intelligence

---
⭐ If you find this project useful, feel free to star this repository!
