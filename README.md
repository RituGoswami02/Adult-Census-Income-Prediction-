# Adult-Census-Income-Prediction-
“End-to-end analytics project on Adult Census Income dataset with Decision Tree classifier, data preprocessing, model evaluation, and feature analysis.”

Table of Content :[ Project Overview , Dataset Description , Technologies Used , Data Preprocessing , Model Used , Model Performance , Feature Importance, Confusion Matrix , Conclusion ]

##Project Overview :
This project predicts whether a person’s annual income exceeds $50,000 using demographic and employment attributes.
It is based on the Adult Census Income Dataset (UCI Repository / Kaggle).
The goal was to build a clean, industry-standard, and research-friendly machine learning pipeline demonstrating:
Data preprocessing
Exploratory data analysis
Feature engineering
Model training & evaluation
Interpretation (feature importance)
Ethical and fairness considerations

##Dataset Description :
The dataset includes 48,842 records with attributes such as:
Age
Education
Workclass
Marital-status
Occupation
Hours-per-week
Capital-gain / Capital-loss
Native country
Target variable:
0 → Income ≤ $50K
1 → Income > $50K

##Technologies Used :
Python
Pandas
NumPy
Scikit-Learn
Matplotlib / Seaborn
Decision Tree Classifier

##Data Preprocessing :
The following steps were performed:
✔ Handling missing values
Converted or removed missing categories (“?” values).
✔ Encoding categorical variables
Used Label Encoding for decision tree compatibility.
✔ Train-test split
Train: 80%
Test: 20%
✔ Feature scaling
Not required for tree-based models.

##Model Used: Decision Tree Classifier :
A Decision Tree was trained for interpretability and feature-level understanding, which is useful for:
Job portfolios (clarity)
PhD research (explainability)
Industry ML (transparent decisions)

##Model Performance :
Evaluation Metrics (Extracted from Kaggle notebook):
Metric	Score
Accuracy	~85%
Weighted F1-score	~0.84
Class 0 Precision/Recall	~0.86
Class 1 Precision/Recall	~0.77

✔ Model performs well on majority class
✔ Acceptable performance on minority class (income >50K)

##Feature Importance :
Yes — feature importance was generated using the fitted tree model.
Top contributing features typically include:
Capital-gain
Education-num
Hours-per-week
Age
Occupation
These features strongly influence income prediction.

##Confusion Matrix :
You generated a confusion matrix showing:
Strong overall accuracy
Some false negatives (common due to class imbalance)

##Conclusion :
The Decision Tree model successfully predicts adult income with ~85% accuracy, providing explainable insights into socio-economic factors affecting earnings.
The project demonstrates:
Clean ML workflow
Solid understanding of preprocessing
Model evaluation skills
Interpretation ability
Real applied analytics — valuable for jobs and academic selection
