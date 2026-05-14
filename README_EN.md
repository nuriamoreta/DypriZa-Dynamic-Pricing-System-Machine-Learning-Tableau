# 🇬🇧 DyPriZa | Dynamic Pricing Intelligence for Hospitality
## 📌 Executive Summary

DyPriZa is a Dynamic Pricing project applied to the hospitality industry, focused on optimizing pricing strategies through data analysis, machine learning, and executive visualization.

The project was developed as an MVP (Minimum Viable Product) aimed at demonstrating how a data-driven system can help maximize revenue (ADR and RevPAR), improve occupancy, and support decision-making in Revenue Management.

The solution integrates exploratory analysis, predictive modeling, and executive Tableau dashboards to transform market data into actionable insights.

## 🧩 Business Problem

In the hospitality sector, many pricing decisions still rely on manual processes, static rules, or non-scalable analysis.

DyPriZa aims to address challenges such as:

- Price optimization based on demand and seasonality
- Market behavior pattern detection
- Vacancy reduction
- RevPAR and ADR improvement
- Centralization and visualization of key KPIs
- Support for data-driven decision making


## 🎯 Project Goal

Develop a reproducible solution capable of recommending optimal pricing for hospitality properties using data analysis and machine learning techniques.


## 🧠 Methodology

**1. Data ingestion and preparation**

Integration of data from Airbnb, AirDNA, and public datasets
Format normalization and quality validation
Duplicate cleaning and outlier treatment

**2. Feature engineering**

Creation of variables related to:
- Temporality
- Seasonality
- Lead time
- Geographic segmentation
- Demand behavior

**3. Predictive modeling**

Evaluation of Machine Learning models for price prediction:
- Linear Regression
- GridSearch
- Accuracy and stability comparisons

**4. Performance evaluation**

Metrics used:
- MAE
- RMSE
- Within5%
- Within10%
- Residual distribution
- Temporal stability

**5. Visualization and reporting**

Development of executive dashboards in Tableau focused on business and Revenue Management.


## 📊 Main Results
**Global model KPIs**

- MAE ≈ 2.3
- RMSE ≈ 2.9
- Within5% ≈ 95%
- Within10% ≈ 99.17%

**Key insights**

Linear Regression showed greater stability and lower error dispersion
Barcelona showed higher volatility during high season
Madrid showed higher error during mid season
June and September reflected greater predictive stability



## 📈 Dashboard & Visualization

The project includes dashboards developed in Tableau for executive analysis and model performance monitoring.

**Implemented visualizations**

- General KPIs
- Actual vs Predicted
- Actual vs Predicted Dispersion
- Residual distribution
- Temporal error evolution
- Model comparisons
- Segmented analysis by city and season

**Dashboard screenshots**

General KPIs and prediction
<img width="1351" height="756" alt="image" src="https://github.com/user-attachments/assets/006bdc07-9968-47e7-a837-98a4aebd934e" />

Error evolution and segmentation
<img width="1348" height="748" alt="image" src="https://github.com/user-attachments/assets/e91c5402-f3dd-40b5-8ad1-df04a868b475" />


Model comparison
<img width="1348" height="748" alt="image" src="https://github.com/user-attachments/assets/52454f42-543e-4e97-8d41-9ff59fc43cd5" />



## 🛠️ Technologies Used
**Languages and libraries**

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

**Visualization**

Tableau

**Environment**

Jupyter Notebook
Anaconda



## 💼 Demonstrated Skills
**Data Analytics**

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- KPI Analysis
- Business Intelligence

**Machine Learning**

- Model Evaluation
- Regression Models
- Error Analysis
- Predictive Analytics

**Revenue Management**

- Dynamic Pricing
- ADR / RevPAR Analysis
- Occupancy Optimization
- Demand Analysis

**Data Visualization**

- Executive Dashboards
- Tableau Reporting
- Business Storytelling



## 🚀 Roadmap / Next Steps
- Data ingestion automation
- Competitive benchmarking integration
- 30-day forecast development
- Price-demand elasticity implementation
- Recommendation API
- Scenario simulation and operational alerts



## 📁 Project Structure

DyPriZa/

│

├── notebooks/

├── src/

├── data/

├── dashboards/

├── assets/

└── README.md



## 📂 Dataset

The data folder is not publicly shared due to confidentiality restrictions.

The project was developed using public datasets and real hospitality industry data.
