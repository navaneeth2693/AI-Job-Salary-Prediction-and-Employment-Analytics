# Course Assignment 1 | Supervised Machine Learning
**Supervisor:** Prof. Raja Hashim Ali

---

## Project Overview

This project applies supervised machine learning and data analysis techniques to the **Global AI Job Market & Salary Trends 2025** dataset to study AI job roles, salary patterns, skill demand, company characteristics, and employment trends across countries.

The goal is to understand how factors such as job title, experience level, company size, employment type, remote work, education requirements, and required skills influence AI salary outcomes. In addition, predictive models are built to estimate **salary in USD** for AI-related job positions.

The project is structured around seven research questions covering salary analysis, job market trends, feature relationships, and predictive modeling.

---

## Dataset

| Attribute   | Details |
| ----------- | ------- |
| **Name**    | Global AI Job Market & Salary Trends 2025 |
| **Source**  | https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025 |
| **Rows**    | 15,000+ AI job records |
| **Columns** | Use the downloaded CSV columns from the Kaggle dataset |
| **Domain**  | AI Job Market and Salary Analytics |

### Target Variables

| Type                     | Variable |
| ------------------------ | -------- |
| **Primary (Regression)** | `salary_usd` |
| **Secondary**            | `job_title`, `experience_level`, `employment_type`, `remote_ratio` |

### Key Features

* Job title
* Experience level
* Employment type
* Company location
* Employee residence
* Company size
* Remote work ratio
* Education required
* Required skills
* Industry
* Salary in USD

---

## Repository Structure

```bash
global-ai-job-market-salary-ml-assignment/
│
├── RQ1-checkpoint.ipynb
├── RQ2-checkpoint.ipynb
├── RQ3-checkpoint.ipynb
├── RQ4-checkpoint.ipynb
├── RQ5-checkpoint.ipynb
├── RQ6-checkpoint.ipynb
├── RQ7-checkpoint.ipynb
│
├── figures/
├── tables/
│
├── REQUIREMENT.ipynb
└── README.md
```

---

## Research Questions

| #   | Research Question | Notebook |
| --- | ----------------- | -------- |
| RQ1 | How accurately can machine learning models predict AI job salaries? | RQ1-checkpoint.ipynb |
| RQ2 | Which job-related features have the strongest influence on salary prediction? | RQ2-checkpoint.ipynb |
| RQ3 | Does remote work ratio significantly affect salary levels? | RQ3-checkpoint.ipynb |
| RQ4 | How does experience level impact salary in AI-related jobs? | RQ4-checkpoint.ipynb |
| RQ5 | Which industries offer the highest salaries for AI professionals? | RQ5-checkpoint.ipynb |
| RQ6 | Does company size influence compensation packages? | RQ6-checkpoint.ipynb |
| RQ7 | Can job description length and benefits score improve salary prediction performance? | RQ7-checkpoint.ipynb |

---

## Models Used

* Linear Regression
* Decision Tree Regressor
* k-Nearest Neighbors Regressor
* Random Forest Regressor
* XGBoost Regressor
* Support Vector Regression (SVR)

---

## How to Run on Kaggle

1. Go to https://www.kaggle.com and log in
2. Open dataset:
   https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025
3. Click **New Notebook**
4. Upload the `.ipynb` files
5. Use dataset path:

```bash
/kaggle/input/global-ai-job-market-and-salary-trends-2025/
```

6. Click **Run All**

> Each notebook is independent and can be run separately.

---

## Generated Outputs

### Figures

| Figure_1_1_RQ1_actual_vs_predicted.png |
| Figure_1_2_RQ1_correlation_heatmap.png |
| Figure_1_3_RQ1_model_comparison.png |
| Figure_1_4_RQ1_salary_distribution.png |
| Figure_2_1_RQ2_actual_vs_predicted.png |  
| Figure_2_2_RQ2_correlation_heatmap.png | 
| Figure_2_3_RQ2_feature_importance_bar_chart.png | 
| Figure_2_4_RQ2_salary_distribution.png | 
| Figure_3_1_RQ3_boxplot.png |
| Figure_3_2_RQ3_scatter.png | 
| Figure_4_1_rq4_barplot_avg_salary.png | 
| Figure_4_2_rq4_boxplot_salary_by_experience.png | 
| Figure_4_3_rq4_feature_importance.png | 
| Figure_4_4_rq4_scatter_experience_salary.png | 
| Figure_5_1_RQ5_salary_boxplot.png | 
| Figure_5_2_RQ5_top10_locations_salary.png | 
| Figure_5_3_RQ5_top_locations_jobcount.png | 
| Figure_6_1_RQ6_benefits_barplot.png | 
| Figure_6_2_RQ6_model_r2.png | 
| Figure_6_3_RQ6_salary_boxplot.png | 
| Figure_7_1_RQ7_correlation_heatmap.png | 
| Figure_7_2_RQ7_description_vs_salary.png | 
| Figure_7_3_RQ7_model_comparison.png | 


### Tables

| Table_1_1_RQ1_correlation_table.csv | 
| Table_1_2_RQ1_model_results.csv | 
| Table_1_3_RQ1_sample_dataset.csv | 
| Table_2_1_RQ2_feature_importance.csv | 
| Table_2_2_RQ2_model_performance.csv | 
| Table_2_3_RQ2_predictions.csv | 
| Table_3_1_rq3_remote_salary_dataset.csv |
| Table_3_2_RQ3_anova_results.csv |
| Table_3_3_RQ3_regression_results.csv |
| Table_3_4_RQ3_remote_salary_summary.csv |
| Table_4_1_RQ4_processed_dataset.csv | 
| Table_4_2_anova_results.csv | 
| Table_4_3_avg_salary_by_experience.csv | 
| Table_4_4_experience_encoding_table.csv | 
| Table_4_5_feature_importance.csv | 
| Table_4_6_ml_model_results.csv | 
| Table_4_7_processed_rq4_dataset.csv | 
| Table_5_1_RQ5_full_location_salary_table.csv | 
| Table_5_2_RQ5_location_salary_table.csv | 
| Table_6_1_RQ6_company_size_dataset.csv | 
| Table_6_2_RQ6_company_size_summary.csv | 
| Table_6_3_RQ6_company_size_summary.csv | 
| Table_6_4_RQ6_model_results.csv | 
| Table_7_1_RQ7_dataset.csv | 
| Table_7_2_RQ7_feature_importance.csv | 
| Table_7_3_RQ7_model_comparison.csv | 

## Key Findings

* Higher experience levels are expected to be associated with higher AI salaries.
* Specialized AI job titles may show stronger salary outcomes than general roles.
* Remote and hybrid roles may differ in salary depending on country and company type.
* Company size and industry can influence salary distribution.
* Country-level salary patterns reveal differences in global AI labor markets.
* Machine learning models can be used to predict salary from job-related features.
* Technical skills such as machine learning, Python, cloud platforms, NLP, and computer vision may be linked with higher-paying roles.

---

## Requirements

Main libraries:
pandas==2.2.2
numpy==1.26.4
matplotlib==3.8.4
seaborn==0.13.2
scikit-learn==1.4.2
xgboost==2.0.3
shap==0.44.1
jupyter==1.0.0
scipy==1.13.1
plotly==5.22.0
statsmodels==0.14.2

## How to Run


### Step 1: Download Dataset

Go to:
https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025

Download the dataset, extract it, and place the CSV file in your project folder.

### Step 2: Run Notebooks Locally

Open Jupyter Notebook or VS Code, navigate to the project folder, and run:

```bash
jupyter notebook
```

Open any `RQ*.ipynb` file and click **Run All**.

### Step 3: Run on Kaggle Alternative

Go to https://www.kaggle.com and log in.
Open the dataset page.
Click **New Notebook**.
Upload your `.ipynb` files.
Use dataset path:

```bash
/kaggle/input/global-ai-job-market-and-salary-trends-2025/
```

Click **Run All**.
