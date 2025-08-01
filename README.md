# Lead Scores Analysis

This project focuses on predicting the likelihood of lead conversion using logistic regression. It includes data preprocessing, EDA, feature engineering, and model building.

---

## Problem Statement

X Education, an online course provider for professionals, receives numerous leads daily from various digital channels. However, with a low lead-to-sale conversion rate (~30%), their sales team struggles to prioritize high-potential leads. The goal is to build a machine learning model that assigns a lead score to each lead, helping the sales team focus on those most likely to convert. The target is to improve the conversion rate to around 80% by identifying and prioritizing ‘Hot Leads’.

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Workflow

1. *Data Preprocessing*  
   - Removed irrelevant and missing values (~30% of data)
   - Encoded categorical variables
   - Scaled numerical features

2. *Exploratory Data Analysis (EDA)*  
   - Identified key correlations
   - Visualized lead behavior patterns

3. *Model Building (Logistic Regression)*  
   - Trained a classification model
   - Evaluated using accuracy, ROC-AUC, confusion matrix

4. *Insights & Recommendations*  
   - Feature importance identified top lead indicators
   - Recommendations provided for marketing targeting

---

## Results

- *Accuracy*: 87%
- *ROC-AUC Score*: 0.89
- *Key Predictors*: Page Views, Time on Website, Source

![Confusion Matrix](images/confusion_matrix.png)

---

## EDA Highlights

- Leads from organic sources had higher conversion rates
- Optimal browsing time on website correlated with conversion

![EDA Heatmap](images/eda_heatmap.png)

---

## Project Structure

Lead-Scores-Analysis/
├── README.md
├── requirements.txt
├── data/
│ └── leads.csv
├── notebooks/
│ └── lead_score_analysis.ipynb
├── scripts/
│ ├── eda.py
│ └── model.py
├── images/
│ ├── confusion_matrix.png
│ └── eda_heatmap.png
├── output/
│ └── model_results.csv
└── project_report.pdf

---

## Dataset

- The dataset contains behavioral and demographic data for potential customers.
- You can find the CSV file inside the data folder.
- [Optional: Add source link if from Kaggle or public domain]

---

## Author

*Kiran Kumar Das*  
📍 Bhubaneswar, Odisha  
📧 [Email-ID](mailto:2041004012.kirankumardas@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/kirankumardas16) | [GitHub](https://github.com/Kiran8053)
