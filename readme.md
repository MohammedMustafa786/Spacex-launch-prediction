SpaceX Launch Analysis and Predictive Modeling
 Project Overview
This project is a Data Science Capstone analyzing SpaceX launch records. It combines data collection, wrangling, visualization, and machine learning to predict launch outcomes. Interactive dashboards and classification models provide insights into payload ranges, booster versions, and site performance.

 Objectives
Collect SpaceX launch data via API and web scraping

Clean and preprocess datasets for analysis

Perform SQL‑based exploratory queries

Build interactive dashboards with Plotly Dash

Train and evaluate classification models (Logistic Regression, SVM, Decision Tree, KNN)

Compare model accuracies and validate with confusion matrices

Deliver insights on factors influencing launch success

 Workflow
Data Collection

SpaceX REST API + web scraping

Data stored in CSV and SQLite formats

Data Wrangling

Cleaning payload mass, booster categories, and launch site data

Encoding categorical variables

Exploratory Data Analysis (EDA)

SQL queries for site counts, payload ranges, success ratios

Visualizations: pie charts, scatter plots, folium maps

Interactive Dashboards

Built with Plotly Dash

Features: dropdown filters, payload sliders, site‑specific charts

Predictive Modeling

Models: Logistic Regression, SVM, Decision Tree, KNN

Accuracy comparison via bar chart

Confusion matrix for best model (Decision Tree)

Conclusion

Decision Tree achieved highest accuracy (88%)

Payload size, booster version, and site infrastructure strongly influence success

 Key Visual Assets
Pie chart: Success launches by site

Scatter plot: Payload vs. Launch Outcome

Bar chart: Classification Model Accuracy Comparison

Confusion matrix: Decision Tree predictions

Interactive dashboard screenshots

 Assets & Deliverables
Python scripts for data wrangling, visualization, and machine learning

SQL queries for exploratory analysis

Jupyter Notebook outputs documenting each step

Interactive Dash app with dropdowns and sliders

Datasets: SpaceX launch records (CSV, SQLite)

Charts & screenshots included in presentation slides

 Installation & Quick Start
Clone the repository:

bash
git clone https://github.com/yourusername/spacex-launch-analysis.git
cd spacex-launch-analysis
Install dependencies:

bash
pip install -r requirements.txt
Run Jupyter Notebook for EDA:

bash
jupyter notebook spacex_analysis.ipynb
Launch the Dash app:

bash
python spacex_dash_app.py
Open browser at http://127.0.0.1:8050/ to view dashboards.

 Results
Decision Tree model achieved 88% accuracy, outperforming SVM (85%), Logistic Regression (82%), and KNN (80%)

Confusion matrix confirmed strong predictive capability with minimal misclassifications

Payload range (4000–6000 kg) and advanced booster versions (FT, B5) showed highest success rates

 Conclusion
This project demonstrates the end‑to‑end application of data science in aerospace. Interactive dashboards and machine learning models provided actionable insights into SpaceX’s launch performance, highlighting the engineering progress and reliability of newer boosters.

 Future Work
Extend dataset with more recent launches

Apply ensemble methods (Random Forest, XGBoost) for improved accuracy

Deploy dashboards as a web app for public access

Explore feature importance for deeper insights into launch success drivers