# AI-Based Fraud Detection System

## Overview

This project presents a comprehensive approach to detecting fraudulent financial transactions using machine learning and deep learning techniques. The system analyzes transaction patterns to identify anomalies and classify transactions as legitimate or fraudulent. It is designed to handle highly imbalanced datasets and simulate real-world fraud detection scenarios.

---

## Objectives

* Develop an accurate and reliable fraud detection model
* Address class imbalance in financial datasets
* Compare the performance of traditional machine learning and deep learning models
* Build a modular and extensible pipeline for experimentation and analysis

---

## Technologies Used

* Programming Language: Python
* Libraries: Pandas, NumPy, Scikit-learn, TensorFlow/Keras
* Visualization: Matplotlib, Seaborn
* Development Environment: Jupyter Notebook, Visual Studio Code

---

## Project Structure

```bash
AI-Based-Fraud-Detection/
│
├── BalanceDataset.py
├── DeepLearningModels.py
├── MachineLearningModels.py
├── README.md
│
├── creditcard/
│   ├── creditcard.ipynb
│   ├── feature engineering and selection notebooks
│
├── ieee-fraud-detection/
│   ├── ieee-fraud-detection.ipynb
│
├── Synthetic Financial Datasets For Fraud Detection/
│   ├── dataset notebook
│
└── Project Reports/
    ├── Final report (PDF)
```

---

## Dataset Description

The project utilizes multiple datasets to ensure robustness and generalization:

* Credit Card Fraud Detection Dataset
* IEEE Fraud Detection Dataset
* Synthetic Financial Dataset

These datasets include transaction-level features such as:

* Transaction amount and timestamp
* Engineered numerical features (e.g., PCA components)
* Binary classification label (fraud or non-fraud)

---

## Methodology

### Data Preprocessing

* Handling missing values and noise
* Feature scaling and normalization
* Addressing class imbalance using appropriate techniques

### Feature Engineering

* Correlation-based feature selection
* Outlier detection and suppression
* Dimensionality reduction techniques

### Model Development

#### Machine Learning Models

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting (XGBoost)

#### Deep Learning Models

* Artificial Neural Networks
* Fully Connected Dense Architectures

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

---

## Results

The implemented models demonstrate strong performance in detecting fraudulent transactions, particularly in improving recall for the minority class. Comparative analysis highlights the effectiveness of ensemble and deep learning approaches in handling complex patterns within financial data.

---

## Installation and Usage

### Clone the Repository

```bash
git clone https://github.com/amitgupta226571/Fraud-Detection.git
cd Fraud-Detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

To execute machine learning models:

```bash
python MachineLearningModels.py
```

To explore experiments and analysis:

```bash
jupyter notebook
```

---

## Future Work

* Deployment as a real-time fraud detection system
* Integration with web frameworks such as Streamlit or Flask
* Incorporation of Explainable AI techniques (e.g., SHAP, LIME)
* Hyperparameter optimization and model tuning
* Integration with streaming data pipelines

---

## Author

Amit Gupta
LinkedIn: https://www.linkedin.com/in/amit-gupta-559418315/
GitHub: https://github.com/amitgupta226571

---

## License

This project is distributed under the MIT License.

---

## Acknowledgements

* Public datasets from Kaggle and IEEE
* Open-source machine learning community
* Research contributions in fraud detection and anomaly detection
