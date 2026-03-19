# Path-Finder-Optimization-Algorithm
Swarm Based - PFO

# 🧠 Breast Cancer Classification using Path Finder Optimization (PFO)

## 📌 Project Overview
This project focuses on improving the performance of machine learning models for breast cancer classification using a meta-heuristic optimization algorithm called Path Finder Optimization (PFO).

The main goal is to:
- Select optimal features using PFO
- Improve classification accuracy
- Compare performance before and after optimization

---

## 🚀 Key Features
- Implementation of Path Finder Optimization Algorithm (PFO)
- Feature selection using optimization
- Multiple ML models comparison:
  - Logistic Regression
  - Decision Tree
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Random Forest (Ensemble)
- Evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC Curve
  - Confusion Matrix
- Both Train-Test Split and K-Fold Cross Validation

---

## 📂 Dataset
- Dataset used: Breast Cancer Dataset
- Preprocessing steps:
  - Dropping unnecessary columns (e.g., id)
  - Encoding categorical labels using LabelEncoder

---

## ⚙️ Technologies Used
- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- Custom Metaheuristic Algorithm (PFO)

---

## 🧪 Methodology

### 1. Without Optimization
- Models are trained directly on dataset
- Performance metrics are recorded

### 2. With Optimization (PFO)
- PFO selects the most relevant features
- Models are retrained using selected features
- Performance is compared with baseline

---

## 🧠 Path Finder Optimization (PFO)
PFO is a nature-inspired metaheuristic algorithm that simulates the behavior of a pathfinder leading a group to find optimal solutions.

Steps:
1. Initialize population
2. Identify best solution (pathfinder)
3. Update positions of agents
4. Evaluate fitness
5. Repeat until convergence

Objective Function Used:
- Sphere Function (Square Function)

---

## 📊 Models Implemented
- Logistic Regression
- Decision Tree
- KNN
- SVM
- Random Forest

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- Specificity
- F1 Score
- Cohen’s Kappa
- Matthews Correlation Coefficient (MCC)
- ROC Curve & AUC Score
- Confusion Matrix

---

## 🔁 Validation Techniques
- Train-Test Split (70% training, 30% testing)
- K-Fold Cross Validation (K = 10)

---

## 📊 Results
- Feature selection using PFO improves model performance
- Reduced feature space leads to better accuracy and faster computation
- Ensemble models (Random Forest) generally perform best

---

## 📁 Project Structure
