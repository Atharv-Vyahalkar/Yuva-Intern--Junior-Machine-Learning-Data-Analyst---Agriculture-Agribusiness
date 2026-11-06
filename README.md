# Yuva Intern – Junior Machine Learning Data Analyst
### Agriculture & Agribusiness

## About This Repository

This repository documents my learning experience and technical work as part of the **Yuva Intern – Junior Machine Learning Data Analyst (Agriculture & Agribusiness)** program.

The primary focus is exploring agricultural datasets, understanding data patterns, performing data preprocessing, and applying machine learning techniques to agricultural problems.

The repository contains weekly assignments, Google Colab notebooks, datasets, experimental results, visualizations, and technical reports documenting the complete workflow.

## Objectives

- Develop practical skills in data analysis and machine learning.
- Explore publicly available Indian agricultural datasets.
- Understand agricultural data characteristics and patterns.
- Perform data cleaning, preprocessing, and transformation.
- Develop and evaluate regression models.
- Interpret experimental results using appropriate evaluation metrics.
- Maintain technical documentation of the work performed.

## Weekly Progress

### Week 1 – Exploratory Data Analysis (EDA)

**Focus:** Understanding agricultural data and identifying meaningful patterns.

Key activities:
- Agricultural dataset exploration.
- Understanding Area, Production, and Yield (APY).
- State-wise and district-wise analysis.
- Crop and seasonal distribution analysis.
- Statistical summaries and data visualizations.
- Identification of dataset limitations and inconsistencies.

**Deliverable:** Week 1 EDA notebook and technical report.

### Week 2 – Data Preprocessing and Transformation

**Focus:** Preparing agricultural data for machine learning applications.

Key activities:
- Missing-value identification and handling.
- Duplicate record inspection.
- Outlier investigation.
- Numerical data transformation and normalization.
- Categorical variable encoding.
- Preparation of a cleaned, ML-ready dataset.

**Deliverable:** Week 2 preprocessing notebook and technical report.

### Week 3 – Machine Learning Model Development

**Focus:** Designing and evaluating machine learning models for crop yield prediction using 2024–25 agricultural data.

Algorithms implemented:
- Dummy Regressor
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Tuned Random Forest Regressor

Key activities:
- Feature selection and target identification.
- Prevention of target leakage.
- Training and testing data separation.
- Model development and comparison.
- Evaluation using MAE, RMSE, and R².
- Hyperparameter tuning using RandomizedSearchCV.
- Cross-validation and residual analysis.
- Feature importance investigation.
- Model performance interpretation.

**Best reported model:** Tuned Random Forest Regressor.

**Test performance:**
- RMSE: 0.4577
- R²: 0.7845

*Note: These metrics are calculated in the transformed and standardized target space.*

**Deliverable:** Week 3 machine learning notebook, experimental outputs, and technical report.

## Technology Stack

| Category | Tools and Technologies |
|---|---|
| Programming Language | Python |
| Development Environment | Google Colab, Jupyter Notebook |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Data Format | CSV |
| Documentation | Microsoft Word |
| Version Control | Git and GitHub |

## Repository Structure

```text
Yuva-Intern/
│
├── Week-1/
│   ├── EDA_Notebook.ipynb
│   ├── Dataset/
│   └── Week1_Technical_Report.docx
│
├── Week-2/
│   ├── Preprocessing_Notebook.ipynb
│   ├── Dataset/
│   └── Week2_Technical_Report.docx
│
├── Week-3/
│   ├── Week3_Final_Experiment.ipynb
│   ├── Model_Comparison_Results.csv
│   ├── Feature_Importance.csv
│   ├── Prediction_Results.csv
│   └── Week3_Technical_Report.docx
│
└── README.md
```

*The folder names above are illustrative. Adjust them to match the actual repository structure.*

## Learning Outcomes

Through this work, I have gained practical experience in:

- Exploring and understanding real-world agricultural datasets.
- Performing exploratory data analysis.
- Identifying data quality issues.
- Cleaning and transforming datasets.
- Applying machine learning regression algorithms.
- Evaluating models using statistical performance metrics.
- Performing hyperparameter optimization.
- Interpreting model outputs and identifying limitations.
- Preparing structured technical documentation.

## Important Note

This repository represents an academic learning and practical implementation experience. The crop yield prediction experiment is based on a single agricultural season (2024–25) and should not be interpreted as a validated future-season forecasting system.

All findings and model performance results are specific to the dataset and experimental methodology used.

## Acknowledgement

This repository is maintained as part of my Yuva Intern learning experience in the **Junior Machine Learning Data Analyst – Agriculture & Agribusiness** domain.

The objective is to continuously strengthen my understanding of data analytics, machine learning, experimentation, and practical problem-solving.

---

**Author:** Atharv Vyahalkar

**Domain:** Machine Learning | Data Analytics | Agriculture & Agribusiness
