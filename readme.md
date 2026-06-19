# SpaceX Launch Analysis and Predictive Modeling

## Project Overview

This project is a **Data Science Capstone** that analyzes SpaceX launch records. It combines data collection, preprocessing, exploratory data analysis (EDA), interactive visualization, and machine learning to predict launch outcomes.

The project demonstrates an end-to-end data science workflow, from acquiring raw launch data to building predictive models and interactive dashboards that provide insights into launch performance.

---

## Objectives

- Collect SpaceX launch data using REST API and web scraping.
- Clean and preprocess datasets for analysis.
- Perform SQL-based exploratory data analysis.
- Build interactive dashboards using Plotly Dash.
- Train and evaluate multiple classification models.
- Compare model performance using accuracy scores and confusion matrices.
- Identify the key factors influencing successful SpaceX launches.

---

# Project Workflow

## 1. Data Collection

- Collected launch data from the SpaceX REST API.
- Extracted additional information through web scraping.
- Stored datasets in:
  - CSV format
  - SQLite database

---

## 2. Data Wrangling

Performed data preprocessing tasks including:

- Handling missing values
- Cleaning payload mass data
- Standardizing booster version categories
- Cleaning launch site information
- Encoding categorical variables for machine learning

---

## 3. Exploratory Data Analysis (EDA)

Performed SQL queries to analyze:

- Launch counts by site
- Payload mass distribution
- Success vs. failure ratios
- Booster version statistics

Created visualizations including:

- Pie charts
- Scatter plots
- Folium maps
- Statistical summaries

---

## 4. Interactive Dashboard

Developed interactive dashboards using **Plotly Dash**.

### Features

- Launch site dropdown filter
- Payload range slider
- Site-wise success analysis
- Interactive scatter plots
- Dynamic charts based on user selection

---

## 5. Predictive Modeling

Implemented and compared the following classification algorithms:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)

### Model Evaluation

Models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Model Comparison Bar Chart

---

## 6. Results

The **Decision Tree** classifier achieved the highest performance.

| Model | Accuracy |
|--------|----------|
| Decision Tree | **88%** |
| SVM | 85% |
| Logistic Regression | 82% |
| KNN | 80% |

Key findings:

- Decision Tree achieved the highest accuracy (**88%**).
- Confusion matrix showed minimal misclassifications.
- Payload ranges between **4000–6000 kg** had the highest success rates.
- Advanced booster versions (**FT** and **B5**) demonstrated superior launch reliability.

---

## Key Visual Assets

The project includes the following visualizations:

- Success Launches by Site (Pie Chart)
- Payload vs. Launch Outcome (Scatter Plot)
- Classification Model Accuracy Comparison (Bar Chart)
- Decision Tree Confusion Matrix
- Interactive Plotly Dash Dashboard Screenshots

---

## Project Structure

```text
spacex-launch-analysis/
│
├── data/
│   ├── launch_data.csv
│   ├── spacex.sqlite
│
├── notebooks/
│   ├── spacex_analysis.ipynb
│
├── dashboard/
│   ├── spacex_dash_app.py
│
├── sql/
│   ├── exploratory_queries.sql
│
├── images/
│   ├── pie_chart.png
│   ├── scatter_plot.png
│   ├── confusion_matrix.png
│   ├── dashboard.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Assets & Deliverables

The project includes:

- Python scripts for:
  - Data collection
  - Data wrangling
  - Visualization
  - Machine learning
- SQL queries for exploratory analysis
- Jupyter Notebook documenting the complete workflow
- Interactive Plotly Dash application
- SpaceX datasets (CSV and SQLite)
- Charts and presentation screenshots

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/yourusername/spacex-launch-analysis.git
cd spacex-launch-analysis
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Jupyter Notebook

```bash
jupyter notebook spacex_analysis.ipynb
```

---

## Launch the Dashboard

```bash
python spacex_dash_app.py
```

Open your browser and visit:

```text
http://127.0.0.1:8050/
```

---

# Technologies Used

## Programming Language

- Python

## Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Dash
- Folium
- Scikit-learn
- SQLite3

## Machine Learning Models

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)

---

# Results

### Best Performing Model

**Decision Tree**

**Accuracy:** **88%**

### Performance Comparison

| Model | Accuracy |
|--------|----------|
| Decision Tree | 88% |
| SVM | 85% |
| Logistic Regression | 82% |
| KNN | 80% |

### Key Insights

- Decision Tree produced the best classification performance.
- Payload mass significantly influenced launch success.
- FT and B5 boosters achieved the highest reliability.
- Launch site infrastructure positively impacted mission outcomes.

---

# Conclusion

This project demonstrates an end-to-end data science workflow applied to aerospace analytics.

From collecting raw launch data to deploying interactive dashboards and predictive machine learning models, the project provides valuable insights into SpaceX launch performance.

The analysis highlights how payload mass, booster version, and launch site characteristics influence mission success while showcasing practical applications of data science techniques in real-world aerospace engineering.

---

# Future Work

Potential improvements include:

- Integrating more recent SpaceX launch data
- Implementing ensemble models such as:
  - Random Forest
  - XGBoost
- Deploying the dashboard as a cloud-hosted web application
- Performing feature importance analysis
- Incorporating real-time launch data from the SpaceX API

---

# Author

**Mohammad Mustafa**

Data Science | Machine Learning | Python | SQL | Data Visualization
