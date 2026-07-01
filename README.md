Classification of Arrhythmia (ECG Data)

A machine learning project that classifies ECG data to detect different types of cardiac arrhythmia using classical machine learning algorithms. The project includes data preprocessing, feature engineering, PCA, SMOTE, and model evaluation. :contentReference[oaicite:0]{index=0}

---

 Features

- ECG data preprocessing
- Missing value handling
- Feature engineering
- PCA for dimensionality reduction
- SMOTE for class balancing
- Multiple ML model comparison
- Performance evaluation

---

Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

Project Structure

```
Classification-of-Arrhythmia/
│── Data/
│── Preprocessing and EDA/
│── Model/
│── Images/
│── final with pca.ipynb
│── requirements.txt
└── README.md
```

---

Installation

```bash
git clone <repository-url>
cd Classification-of-Arrhythmia

python -m venv venv
venv\Scripts\activate    # Windows

pip install -r requirements.txt
```

---

Usage

Run the notebooks in the following order:

1. Data Preprocessing
2. Exploratory Data Analysis (EDA)
3. Model Training and Evaluation

```bash
jupyter notebook
```

---

Models Used

- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree
- Linear SVM
- Kernel SVM
- Random Forest

---

Dataset

- UCI Arrhythmia Dataset
- 452 ECG records
- 279 features
- 16 output classes :contentReference[oaicite:1]{index=1}

---

License

This project is intended for educational and research purposes.