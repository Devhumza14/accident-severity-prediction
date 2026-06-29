# accident-severity-prediction
End-to-end Machine Learning pipeline for predicting US traffic accident severity. Includes memory-optimized ingestion, temporal feature engineering, sparse categorical encoding for high-cardinality geographic data, and statistical feature selection. Achieved 80.05% accuracy.
# US Accidents Severity Prediction

A data science project focused on predicting the severity of traffic accidents using the US Accidents dataset (500k sample). The project demonstrates an end-to-end ML lifecycle from data cleaning to model deployment.

## 🚀 Key Features
* **Memory Optimization:** Implemented sparse coordinate mapping (CSR) to handle high-cardinality features (9,000+ dimensions) within 8 GB RAM constraints.
* **Feature Engineering:** Advanced temporal extraction and median imputation.
* **Pipeline:** Automated preprocessing and statistical feature selection using ANOVA F-tests.
* **Performance:** Achieved **80.05%** accuracy on the test set.

## 🛠 Tech Stack
* **Python**
* **Pandas & NumPy** (Memory-efficient loading)
* **Scikit-Learn** (Pipelines, OneHotEncoding, RandomForest)
* **Matplotlib & Seaborn** (Data visualization)

## 📊 Pipeline Overview


## 📈 Analysis
By leveraging sparse matrices, the model retained critical geographic signals from the 'City' column, significantly improving the classification precision of minority accident severity classes.

## 📝 License
This project is open-source and available for educational purposes.
