# Red Wine Quality Analysis Project

## 1. Project Description

This project provides a comprehensive machine-learning experimentation framework designed to support multiple model families, including regression, classification, clustering, dimensionality reduction, and ensemble learning. The repository contains 16 modular Jupyter notebooks, each dedicated to a specific model or technique, along with reusable Python scripts for data preprocessing, feature scaling, imbalance handling, splitting strategies, and model evaluation.

The goal of the project is to build a reproducible, well-structured machine learning workflow that allows team members to easily test, compare, and analyze a wide range of algorithms across supervised and unsupervised learning tasks.

## 2. Features

* Reusable data preprocessing utilities
* Regression models (Linear, Polynomial, Regularized)
* Classification models (Logistic Regression, SVM, KNN, Decision Trees)
* Ensemble methods (Bagging, Boosting, Stacking)
* Clustering methods (K-Means, Hierarchical, DBSCAN)
* Dimensionality reduction using PCA
* Imbalance handling with SMOTE and undersampling
* Clean modular notebook structure
* Configurable pipeline for consistent experimentation

## 3. Repository Structure

```
/project-root
├── data/
  ├── winequality-red.csv    # original dataset
  ├── Wine_clean.csv         # dataset after EDA          
├── notebooks/
  ├── Exploratory Data Analysis (EDA).ipynb
  ├── 1_Linear Regression.ipynb
  ├── 2_Polynomial Regression.ipynb
  ├── ...
  ├── 15_Principle Component Analysis (PCA).ipynb  
├── src/
  ├── Reusable Function.ipynb                   
├── reports/
  ├── AIL_Report_Group_2.pdf
├── video/           
├── README.md              
└── requirements.txt       
```

## 4. Setup Instructions

### 4.1. Clone the Repository

```bash
git clone https://github.com/tphau29125/FA25_AIL303m_Project_Group2.git
cd FA25_AIL303m_Project_Group2
```

### 4.2. Create and Activate Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate # macOS/Linux
```

### 4.3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4.4. Open the Notebooks

Use Jupyter Notebook or VS Code:

```bash
jupyter notebook
```

## 5. Team Members

| Name     | Role                                                   |
| -------- | ------------------------------------------------------ |
| Nguyen Le Anh Duy      | Leader: Linear Regression, Polynomial Regression, Regularized Regression, Process Management |
| Than Phuc Hau | Member: EDA,Ensemble - Stacking, Imbalance Handling Techniques, K-Means Clustering, Report |
| Vo Minh Huy | Member: EDA, Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machines (SVM) |
| Vo Quang Truong |Member: Hierarchical Agglomerative Clustering, DBSCAN, Principal Component Analysis (PCA), Report |
| Chau Thai Nhat Minh | Member: Decision Trees, Ensemble - Bagging, Ensemble - Boosting, Report |

## 6. License

This project is for academic purposes under the AIL303m course. Redistribution or modification outside coursework requires permission from the project team.

---

For any further additions—badges, diagrams, architectural overviews, or contribution guidelines—please request an update.
