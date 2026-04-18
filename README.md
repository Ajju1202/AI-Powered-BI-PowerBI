# AI-Powered-BI-PowerBI
# AI-Powered Business Intelligence using Power BI

## Project Overview

This project presents an **AI-powered Business Intelligence system** that integrates Machine Learning with Microsoft Power BI to transform traditional dashboards into intelligent decision-support tools.

The system predicts **buyer propensity** and helps businesses prioritize high-value customers using data-driven insights.

---

## Problem Statement

Organizations struggle to identify which customers are most likely to convert. Traditional dashboards only show past data and do not provide predictive insights.

This project solves that problem by:

* Predicting customer purchase probability
* Segmenting prospects into priority groups
* Visualizing insights using Power BI dashboards

---

## Key Features

* Machine Learning Models (Logistic Regression, Random Forest, Decision Tree)
* Buyer Propensity Prediction
* Customer Segmentation (High / Medium / Low Priority)
* Feature Importance Analysis
* Interactive Power BI Dashboard
* Low-code AI + BI integration

---

## Tech Stack

* Python (pandas, numpy, scikit-learn, matplotlib)
* Power BI
* DAX
* Power Query
* Machine Learning Algorithms

---

## Dataset

* **SalesTraining.csv** – 7,819 labeled records
* **ProspectiveBuyer.csv** – 2,059 customer records

---

## Model Performance

Best Model: **Random Forest Classifier**

* Accuracy: 86.2%
* Precision: 84.7%
* Recall: 83.9%
* F1 Score: 84.3%
* AUC-ROC: 0.923

---

## Dashboard Preview

(Add your screenshots here)

![Dashboard](screenshots/dashboard_overview.png)

---

## Key Insights

* High-income customers show higher purchase probability
* Certain occupations have stronger conversion rates
* Model effectively prioritizes high-value prospects

---

## How to Run

1. Install dependencies:

```
pip install -r requirements.txt
```

2. Run Python model:

```
python src/main.py
```

3. Open Power BI:

* Load `Dashboard.pbix`
* Refresh data

---

## Repository Structure

```
src/            → ML code
data/           → datasets
screenshots/    → dashboard images
docs/           → project report
```

---

## Business Impact

* Improves sales targeting
* Increases conversion rates
* Enables data-driven decisions
* Reduces manual effort

---

## Author

**ARJUN**
MCA Student

---

## License

This project is for academic and educational purposes.
