# 🤖 Machine Learning Lab — CSL701-CE35

Welcome to the **Machine Learning Lab** repository for **CSL701-CE35**.

This repository contains the practical experiments, implementations, datasets, and outputs completed as part of the **Machine Learning Laboratory** course. Each experiment focuses on understanding and implementing important concepts and algorithms used in Machine Learning.

---

## 📌 About the Project

**Course:** Machine Learning Lab
**Course Code:** CSL701-CE35
**Domain:** Machine Learning / Artificial Intelligence
**Type:** Laboratory Experiments

The objective of this laboratory is to gain hands-on experience with machine learning techniques, data preprocessing, model training, evaluation, and prediction.

---

## 🎯 Objectives

* Understand fundamental concepts of Machine Learning.
* Implement various Machine Learning algorithms.
* Perform data preprocessing and exploratory data analysis.
* Train and test machine learning models.
* Evaluate model performance using appropriate metrics.
* Visualize datasets and model results.
* Gain practical experience using Python and popular ML libraries.

---

## 🧪 Experiments

The repository contains implementations of the experiments performed during the Machine Learning Lab.

| Experiment    | Description                                           |
| ------------- | ----------------------------------------------------- |
| Experiment 1  | Introduction to Machine Learning and Dataset Analysis |
| Experiment 2  | Data Preprocessing and Data Cleaning                  |
| Experiment 3  | Linear Regression                                     |
| Experiment 4  | Logistic Regression                                   |
| Experiment 5  | K-Nearest Neighbors (KNN)                             |
| Experiment 6  | Decision Tree Classification                          |
| Experiment 7  | Random Forest                                         |
| Experiment 8  | Support Vector Machine (SVM)                          |
| Experiment 9  | K-Means Clustering                                    |
| Experiment 10 | Model Evaluation and Performance Analysis             |

> **Note:** The experiment list can be modified according to the actual experiments included in this repository.

---

## 🛠️ Technologies & Tools

* **Python**
* **Jupyter Notebook**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**

---

## 📂 Repository Structure

```text
CSL701-CE35_Machine-Learning-Lab/
│
├── Experiment-01/
│   ├── experiment1.ipynb
│   └── README.md
│
├── Experiment-02/
│   ├── experiment2.ipynb
│   └── README.md
│
├── Experiment-03/
│   ├── experiment3.ipynb
│   └── README.md
│
├── Experiment-04/
│   ├── experiment4.ipynb
│   └── README.md
│
├── Experiment-05/
│   ├── experiment5.ipynb
│   └── README.md
│
├── datasets/
│
├── requirements.txt
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/CSL701-CE35_Machine-Learning-Lab.git
```

### 2. Navigate to the Project Directory

```bash
cd CSL701-CE35_Machine-Learning-Lab
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

**Linux/macOS:**

```bash
source venv/bin/activate
```

### 5. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 6. Run Jupyter Notebook

```bash
jupyter notebook
```

Open the required experiment notebook and execute the cells sequentially.

---

## 📊 Machine Learning Workflow

The experiments generally follow the standard Machine Learning workflow:

```text
Dataset
   ↓
Data Collection
   ↓
Data Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Visualization & Results
```

---

## 📈 Evaluation Metrics

Depending on the experiment, different evaluation metrics are used, including:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* R² Score
* Silhouette Score

---

## 💻 Example

A basic Machine Learning workflow using Scikit-learn:

```python
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression

X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.2, random_state=42
)

model = LinearRegression()
model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

---

## 📚 Learning Outcomes

After completing these experiments, the following skills are developed:

* Understanding of supervised and unsupervised learning.
* Data preprocessing and feature engineering.
* Implementation of classification and regression algorithms.
* Clustering and pattern discovery.
* Model evaluation and comparison.
* Data visualization.
* Practical use of Python Machine Learning libraries.

---

## 🚀 Future Improvements

* Add more Machine Learning algorithms.
* Compare multiple models on the same dataset.
* Perform hyperparameter tuning.
* Add advanced feature engineering techniques.
* Include interactive visualizations.
* Explore real-world datasets and applications.

---

## 👨‍💻 Author

**Maruti Patil**

🎓 B.E. Computer Engineering
🏫 Yashwantrao Bhonsale Institute of Technology
📍 Mumbai University

---

## ⭐ Repository

If you find this repository useful for learning Machine Learning concepts and laboratory experiments, consider giving it a ⭐.

---

## 📄 License

This project is created for **educational and academic purposes** as part of the Machine Learning Laboratory course.
