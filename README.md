# Credit Card Fraud Detection using Hybrid Ensemble Modeling
Credit card fraud detection using Random Forest, Autoencoder, and Isolation Forest with precision-recall threshold tuning. The project evaluates model performance on imbalanced datasets (Kaggle, PaySim) using F1-score, recall, and precision to optimize fraud classification in real-world scenarios.

---

## Project Overview

This project investigates the challenges of detecting credit card fraud, a rare but critical event in financial transactions, by leveraging a suite of machine learning techniques. The workflow includes data preprocessing, model training, threshold tuning, performance evaluation, and interpretability, with an emphasis on handling severe class imbalance.

---

## Key Features

- **Supervised and Unsupervised Model Comparison:** Evaluate and compare the effectiveness of Random Forest (supervised), Autoencoder, and Isolation Forest (unsupervised) for fraud detection.
- **Precision-Recall Threshold Tuning:** Optimize decision thresholds to maximize fraud detection performance, especially under imbalanced conditions.
- **Comprehensive Evaluation Metrics:** Assess models using F1-score, precision, recall, and Area Under the Curve (AUC) to ensure robust evaluation.
- **Imbalance Handling Techniques:** Apply methods such as resampling, class weighting, and anomaly detection to address skewed class distributions.
- **Explainable and Deployable Models:** Incorporate explainability tools (e.g., feature importance) and provide guidance for model deployment in production environments.

---

## Data Source

- **Kaggle Credit Card Fraud Dataset:** Contains anonymized credit card transactions labeled as fraudulent or legitimate, with a severe class imbalance (fraud cases <1%).
---

## Workflow

1. **Data Preprocessing**
   - Handle missing values and outliers
   - Feature scaling and engineering
   - Train-test split with stratification to preserve class distribution

2. **Modeling**
   - **Random Forest:** Supervised classification leveraging ensemble learning
   - **Autoencoder:** Unsupervised anomaly detection using neural networks
   - **Isolation Forest:** Unsupervised tree-based anomaly detection

3. **Threshold Tuning**
   - Adjust decision thresholds using precision-recall curves to optimize for recall or precision as needed

4. **Imbalance Handling**
   - Techniques such as SMOTE, undersampling, and class weighting to improve minority class detection

5. **Evaluation**
   - Metrics: F1-score, precision, recall, AUC-ROC, and AUC-PR
   - Confusion matrix analysis for each model

6. **Explainability**
   - Feature importance for Random Forest

7. **Deployment**
   - Export trained models for integration into real-time fraud detection pipelines

---

## Results

- **Model Comparison:** Detailed performance metrics and visualizations comparing supervised and unsupervised approaches
- **Threshold Analysis:** Insights into the impact of threshold tuning on model precision and recall
- **Interpretability:** Key features influencing fraud predictions and model transparency

---

## How to Use

1. Clone or download this repository.
2. Install required dependencies from `requirements.txt`.
3. Run the main notebook or script to preprocess data, train models, and evaluate results.
4. Review generated reports and visualizations for insights.
5. Adapt code and models for deployment or further experimentation

---

## Contact

For questions or collaboration, please open an issue or reach out via GitHub or email - rathour.nitin1522002@gmail.com


