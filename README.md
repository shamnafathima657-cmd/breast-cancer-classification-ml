# breast-cancer-classification-ml
Breast Cancer Classification using supervised machine learning models (Logistic Regression, Decision Tree, Random Forest, SVM, and k-NN) with performance comparison on the sklearn dataset.

#  Breast Cancer Classification using Machine Learning

##  goal
This project applies supervised machine learning algorithms to classify breast cancer tumors as **malignant** or **benign** using the Breast Cancer dataset from sklearn.
The goal is to compare multiple classification models and evaluate their performance on a real-world dataset.

---

##  Objective
- Load and preprocess the dataset
- Implement multiple classification algorithms
- Compare model performance
- Identify the best-performing model

---

## Dataset
- Source: Scikit-learn Breast Cancer Dataset
- Features: 30 numerical features (e.g., radius, texture, smoothness)
- Target:
  - 0 → Malignant
  - 1 → Benign

---

## Preprocessing Steps
- Checked for missing values (none found)
- cheked datatypes and duplicates
- Performed train-test split (80:20)
- Applied feature scaling using StandardScaler

Why scaling?
- Ensures all features contribute equally
- Improves performance of distance-based models like KNN and SVM

---

## Models Implemented

### 1. Logistic Regression
- A statistical model used for binary classification
- Works well for linearly separable data

### 2. Decision Tree Classifier
- Splits data into branches based on feature values
- Easy to interpret but prone to overfitting

### 3. Random Forest Classifier
- Ensemble of multiple decision trees
- Reduces overfitting and improves accuracy

### 4. Support Vector Machine (SVM)
- Finds the optimal boundary (hyperplane) between classes
- Effective in high-dimensional spaces

### 5. k-Nearest Neighbors (k-NN)
- Classifies data based on nearest neighbors
- Sensitive to feature scaling

---

##  Model Performance
| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | ~0.97    |
| Decision Tree       | ~0.92    |
| Random Forest       | ~0.96   |
| SVM                 | ~0.97    |
| KNN                 | ~0.94    |

---

## Insights
- **Best Performing Models:** Logistic Regression  & SVM
   These models achieved the highest accuracy
- **Lowest Performance:** Decision Tree Classifier
    These model achieved the lowest accuracy

---

##  Technologies Used
- Python
- Pandas
- Scikit-learn
- NumPy

---

## 📂 Project Structure
