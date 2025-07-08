**Stroke Risk Prediction**

Predicting patient stroke risk from routine clinical data using Decision Tree, Logistic Regression, and Random Forest models.

**Project Overview**

Stroke remains a leading cause of disability and death worldwide. In this project, we leverage routinely collected clinical features age, BMI, hypertension status, heart disease history, smoking status, and more to build and compare three interpretable classifiers for predicting stroke risk. Our end-to-end pipeline ensures robust handling of data quality issues and addresses class imbalance to deliver reliable risk assessments.

**What You’ll Find Here**

•	Data Preprocessing: Dropped irrelevant identifiers and outliers. Median imputation for missing numerical values; mode or "Unknown" fill-ins for categorical gaps.

•	Feature Encoding & Balancing: One-hot encoding of categorical variables (e.g., smoking status, work type) and SMOTE oversampling to correct class imbalance.

•	Model Training: Implementation of Decision Tree, Logistic Regression, and Random Forest classifiers with stratified 80%/20% train/test splits.

•	Evaluation: Evaluation using accuracy, precision, recall, F1-score, and ROC-AUC. Includes ROC curves for visual trade-off analysis.

•	Interpretation & Insights: Feature importance rankings and discussion of key clinical predictors driving stroke risk predictions.

**Getting Started**

1.	Clone the repo: git clone https://github.com/your-username/stroke-prediction.git && cd stroke-prediction
2.	Install dependencies: pip install -r requirements.txt
3.	Prepare the data: python src/data_preprocess.py
4.	Train models: python src/train_models.py
5.	Evaluate results: python src/evaluate.py
   
**Contributing**

7.	Fork the repository and create a feature branch (`git checkout -b feature/YourIdea`).
8.	Commit your changes (`git commit -m "Add description of your improvement"`).
9.	Push to the branch (`git push origin feature/YourIdea`).
10.	Open a Pull Request for review.

**License**

This project is licensed under the MIT License. You are free to use, share, and adapt this work with proper attribution.

