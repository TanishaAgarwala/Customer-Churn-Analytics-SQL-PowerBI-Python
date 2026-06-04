# Customer-Churn-Analysis & Prediction-SQL-Power-BI-Python-
Built an end-to-end customer churn analytics and prediction solution using PostgreSQL, Power BI, Python, Pandas, and Scikit-Learn on 6,400+ customer records, covering data extraction, transformation, visualization, and predictive modeling.

## Project Overview

Customer churn is one of the most critical business challenges for subscription-based and service-oriented companies, as losing existing customers directly impacts revenue and growth.

This project combines SQL, Power BI, and Machine Learning to analyze customer behavior, identify churn drivers, and predict customers who are likely to leave in the future. The objective is to help businesses proactively identify at-risk customers and design targeted retention strategies.

The solution follows an end-to-end analytics workflow, covering data extraction, business analysis, dashboard development, predictive modeling, and reporting.

---

## Business Problem

Customer acquisition costs are significantly higher than customer retention costs. Understanding why customers leave and predicting future churn can help organizations:

* Improve customer retention rates
* Reduce revenue loss
* Identify high-risk customer segments
* Optimize customer engagement strategies
* Support data-driven business decisions

---

## Project Workflow

### 1. Data Preparation & SQL Analysis

* Performed data cleaning and transformation using PostgreSQL.
* Created SQL views to simplify analytical reporting.
* Conducted exploratory business analysis using SQL queries.
* Calculated churn metrics, customer segmentation, revenue impact, and retention patterns.

### 2. Power BI Dashboard Development

Developed interactive dashboards to analyze:

* Customer demographics
* Churn rate and retention trends
* Contract-based churn patterns
* Revenue impact of churn
* Churn categories and reasons
* State-wise customer churn distribution
* Service-level churn analysis

Implemented:

* KPI Cards
* Slicers
* Drill-through functionality
* Tooltips
* Cross-filter interactions
* Dynamic reporting

### 3. Machine Learning Model

Built a Random Forest Classification model using Python and Scikit-Learn.

Key steps:

* Data preprocessing
* Feature engineering
* Label Encoding
* Train-Test Split
* Model Training
* Model Evaluation
* Feature Importance Analysis
* Customer Churn Prediction
<img width="1295" height="518" alt="Py-2" src="https://github.com/user-attachments/assets/df5c30d6-f13e-4efe-a6c1-3f7a78aa46e4" />

### 4. Prediction Reporting

Integrated model predictions back into Power BI to create a churn prediction dashboard and identify customers at high risk of leaving.

---

## Key Business Insights

### Customer Churn Rate

* Total Customers: 6,418
* Churned Customers: 1,732
* Overall Churn Rate: 26.99%

### Major Churn Drivers

* Month-to-month contracts showed higher churn rates compared to long-term contracts.
* Customers with shorter tenure were more likely to churn.
* Customers without support and security services showed elevated churn risk.
* Revenue-related factors and customer tenure significantly influenced churn behavior.
* Certain states and demographic groups exhibited higher churn concentrations.

### Revenue Impact

Customer churn contributes directly to revenue loss, highlighting the importance of retention-focused interventions for high-risk customer segments.

---

## Machine Learning Results

### Model Used

Random Forest Classifier

### Model Performance

* Accuracy: 86%
* Precision: 81%
* Recall: 67%
* F1 Score: 73%

### Feature Importance Analysis

The most influential features for churn prediction included:

* Total Revenue
* Total Charges
* Contract Type
* Monthly Charges
* Age
* Tenure in Months
* State
* Number of Referrals

### Prediction Outcome

The model identified 377 customers as potential churn risks, enabling proactive retention planning and targeted customer engagement.

---

## Tools & Technologies

### Database

* PostgreSQL

### Data Visualization

* Power BI
* DAX
* Power Query

### Programming

* Python

### Python Libraries

* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

### Machine Learning

* Random Forest Classifier
* Label Encoding
* Classification Metrics

---

## Dashboard Features

* Customer Churn Overview Dashboard
* Churn Driver Analysis
* Revenue Impact Analysis
* State-wise Churn Analysis
* Churn Category & Reason Analysis
* Feature Importance Visualization
* Customer Churn Prediction Dashboard

---

## Business Impact

This project demonstrates how analytics and machine learning can work together to move from descriptive reporting to predictive decision-making.

By combining SQL, Power BI, and Machine Learning, the solution enables organizations to:

* Understand why customers leave
* Identify high-risk customers
* Reduce churn-related revenue loss
* Support targeted retention campaigns
* Improve customer lifetime value

---

## Project Outcome

Successfully developed an end-to-end Customer Churn Analytics & Prediction solution integrating:

PostgreSQL → Power BI → Python → Machine Learning → Prediction Dashboard

This project showcases practical skills in data analytics, business intelligence, data visualization, and predictive modeling.

<img width="1072" height="537" alt="D-2" src="https://github.com/user-attachments/assets/2a51c1f5-34cc-40c8-99c0-f209b206edcf" />
<img width="1068" height="534" alt="D-1" src="https://github.com/user-attachments/assets/b18f4bbf-d292-4afe-ba68-53a91e4716f5" />
