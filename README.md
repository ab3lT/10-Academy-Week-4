# Rossmann Pharmaceuticals: Sales Forecasting Challenge (10 Academy Week 4)

## Overview

As a Machine Learning Engineer at Rossmann Pharmaceuticals, you are tasked with creating an end-to-end solution to forecast store sales six weeks in advance. This solution will empower the finance team and store managers to make data-driven decisions by considering factors like promotions, competition, holidays, seasonality, and locality.

---

## Key Tasks

### Task 1: **Exploration of Customer Purchasing Behavior**

1. **Objective:** Understand and analyze the impact of various factors on sales, including promotions, holidays, and assortment types.
2. **Steps:**
   - Clean the data (handle outliers, missing values, and inconsistencies).
   - Conduct exploratory data analysis (EDA) with visualizations.
   - Investigate correlations, seasonal patterns, and customer behavior.
3. **Deliverables:**
   - Jupyter notebook with EDA insights.
   - Logger-based implementation for reproducibility.

### Task 2: **Prediction of Store Sales**

1. **Objective:** Build a machine learning model to forecast daily store sales.
2. **Steps:**
   - **Preprocessing:** Feature engineering and scaling.
   - **Model Building:** Train regression models (e.g., Random Forest) using sklearn pipelines.
   - **Post-prediction Analysis:** Evaluate feature importance and confidence intervals.
   - **Model Serialization:** Save models with timestamps for traceability.
   - **Deep Learning:** Develop an LSTM model for time-series forecasting.
3. **Deliverables:**
   - Serialized models.
   - Jupyter notebook with ML and deep learning implementation.

### Task 3: **Model Serving API**

1. **Objective:** Serve the trained models via a REST API.
2. **Steps:**
   - Develop an API using Flask or FastAPI.
   - Load serialized models for predictions.
   - Implement endpoints to accept inputs and return predictions.
   - Deploy the API for real-time accessibility.
3. **Deliverables:**
   - Fully functional REST API.

---

## Learning Outcomes

### Skills

- Advanced use of **scikit-learn**.
- Feature engineering, model building, and fine-tuning.
- Logging, unit testing, and CI/CD deployment.
- **MLOps** with DVC, MLFlow, and CML.
- Dashboard creation and Python-based API development.

### Knowledge

- Data exploration and predictive analysis.
- Hyperparameter tuning, model comparison, and deep learning.
- Communication of insights and reporting complex findings.

---

## Tutorials Schedule

- **Wednesday:** Data exploration and time-series analysis. *(Tutors: Mahlet, Elias)*
- **Thursday:** Predictive ML and model versioning. *(Tutors: Rediet, Emitinan)*
- **Friday:** Deep Learning (LSTM). *(Tutor: Kerod)*
- **Monday:** API Development. *(Tutor: Elias)*

---

## Key Dates

- **Case Discussion:** Wednesday, 01 Jan 2025, 09:00 UTC.
- **Interim Submission:** Friday, 03 Jan 2025, 20:00 UTC.
- **Final Submission:** Tuesday, 14 Jan 2025, 20:00 UTC.

---

## Competency Mapping

| Competency                   | Contribution Areas                                              |
|------------------------------|-----------------------------------------------------------------|
| Professionalism              | Articulating business values                                   |
| Collaboration & Communication| Reporting to stakeholders                                      |
| Software Development         | Using GitHub for CI/CD, modular coding, and packaging          |
| Python Programming           | Advanced use of Pandas, Numpy, Scikit-learn, etc.             |
| SQL Programming              | Database operations                                           |
| Data Analytics Engineering   | Data filtering, transformation, and warehousing              |
| MLOps & AutoML               | Pipeline design, model versioning                             |
| Deep Learning                | RNNs, LSTMs                                                   |
| Web & Mobile Programming     | Flask/Streamlit for dashboard and API development             |

---

## Submission Requirements

### Interim Submission

- Exploratory analysis insights in 10-20 slides.
- Link to GitHub repository containing Jupyter notebooks.

### Final Submission

- A detailed PDF report suitable for blogging.
- Focus on deep learning models.
- Link to GitHub repository with all code and implementation details.

---

## References

- [Rossmann Store Sales Dataset](https://www.kaggle.com/c/rossmann-store-sales)
- [Time-series forecasting with LSTMs](https://machinelearningmastery.com/time-series-forecasting-with-lstms/)
- [MLOps with DVC](https://dvc.org/)
- Tutorials on Flask, scikit-learn pipelines, and more.

---

Let’s tackle this challenge and create an impactful sales forecasting solution!
