# Felipe Andrade — Data Analytics & Data Science Portfolio

I am a Data Analyst and Data Scientist with a PhD in Animal Biology and over 10 years of experience working with complex real-world datasets, quantitative methods, statistical modeling, and reproducible analytical workflows.

I use **Python, SQL, R, statistics, machine learning, and Power BI** to transform raw data into analytical models, insights, visualizations, and decision-support solutions.

This repository is an index of my main projects across **Data Analytics, Business Intelligence, Customer Analytics, Statistical Analysis, Machine Learning, Experimentation, and Data Engineering**.

## Choose a path

### Data Analyst / BI

Projects focused on:

- SQL and PostgreSQL
- Analytical data modeling and star schemas
- Data quality and semantic layers
- KPI design and business metrics
- Power BI and DAX
- Exploratory analysis and data visualization
- Customer Analytics and business storytelling

### Data Science

Projects focused on:

- Statistical analysis and hypothesis testing
- Predictive modeling and machine learning
- Time-series forecasting
- Feature engineering and model evaluation
- Customer churn and customer value
- A/B testing and causal inference
- Reproducible analytical workflows

## Featured projects

### Data Analyst / BI

| Project | Focus | Main technologies |
|---|---|---|
| [Customer Analytics for Brazilian E-commerce](https://github.com/felipeandrade91/Customer-Analytics-for-Brazilian-E-commerce ) | Analytics Engineering, BI, customer and operational analytics | PostgreSQL, SQL, Power BI, DAX, Star Schema |
| [Customer Segmentation & Customer Lifetime Value](https://github.com/felipeandrade91/customer-segmentation-clv ) | Customer intelligence, segmentation and customer value | PostgreSQL, SQL, Python, Pandas, RFM, CLV |
| [GBIF Amphibian Data Analysis](https://github.com/felipeandrade91/GBIF-Brazilian-Amphibian-Biodiversity-Analysis ) | Exploratory, spatial and temporal analysis | Python, Pandas, Plotly, GLM |
| [Brazilian Anuran Biodiversity Dashboard](https://github.com/felipeandrade91/Brazilian-Anuran-Biodiversity-Dashboard ) | Biodiversity indicators and interactive reporting | Power BI, DAX |

### Data Science

| Project | Focus | Main technologies |
|---|---|---|
| [Sales Forecasting — Rossmann Stores](https://github.com/felipeandrade91/sales-forecasting-rossmann ) | Retail forecasting and predictive modeling | Python, PostgreSQL, Pandas, Scikit-learn, XGBoost |
| [Customer Churn — Modeling and API](https://github.com/felipeandrade91/customer-churn-prediction ) · [API repository](https://github.com/felipeandrade91/customer-churn-api ) | Classification, model evaluation and deployment | Python, SQL, Scikit-learn, XGBoost, FastAPI, Docker |
| [Causal Inference & Experimentation](https://github.com/felipeandrade91/causal-inference-experimentation ) | A/B testing, treatment effects and incrementality | Python, EconML, PSM, IPW, DML, Causal Forest |
| Customer Value Analytics | Analytical foundation, customer features, segmentation and CLV | PostgreSQL, SQL, Python, Pandas, RFM, CLV |

## Project summaries

### Customer Analytics for Brazilian E-commerce

An end-to-end Analytics Engineering and Business Intelligence project using the Brazilian E-Commerce Public Dataset.

The project transforms raw transactional data into a structured analytical environment with:

- PostgreSQL data ingestion
- Data quality validation
- Star Schema dimensional modeling
- SQL-based semantic views
- Business-oriented analytical queries
- Power BI dashboards and DAX measures
- Analysis of sales, customers, logistics, delivery performance, sellers, payments, and satisfaction

The dataset contains approximately **100,000 Brazilian e-commerce orders**. The project answers business questions related to revenue, customer behavior, delivery performance, seller performance, and customer satisfaction.

This project also provides the analytical foundation for the complementary [Customer Segmentation & Customer Lifetime Value](https://github.com/felipeandrade91/customer-segmentation-clv ) project.

### Customer Segmentation & Customer Lifetime Value

A customer intelligence project built on top of transactional data from the e-commerce analytics workflow.

The project includes:

- Customer-level feature engineering
- RFM segmentation
- Historical Customer Lifetime Value analysis
- Revenue concentration analysis
- Customer value distributions
- Customer prioritization and retention-oriented insights
- SQL and Python analytical workflows

The objective is to move from transaction-level data to customer-level insights that can support retention, prioritization, and customer value strategies.

### Sales Forecasting — Rossmann Stores

A machine learning project for retail sales forecasting.

The workflow includes:

- PostgreSQL-based data preparation
- Exploratory time-series analysis
- Temporal feature engineering
- Lag and rolling-window features
- Regression modeling
- Comparison of Linear Regression, Random Forest, and XGBoost
- Evaluation using MAE, RMSE, and R²
- Feature importance analysis
- Retail-oriented forecasting insights

The current project reports the following performance for the final XGBoost model:

- **MAE:** 530.89
- **RMSE:** 822.87
- **R²:** 0.954

The repository documents the modeling workflow and the use of machine learning for retail demand forecasting. Validation strategy, baseline comparisons, and error analysis are important parts of the ongoing project documentation.

### Customer Churn — Modeling and API

An end-to-end customer churn project covering model development and deployment.

The modeling repository includes:

- PostgreSQL-based data preparation
- SQL data quality validation
- Analytical dataset construction
- Exploratory Data Analysis
- Feature engineering
- Classification model development
- Comparison of Logistic Regression, Random Forest, and XGBoost
- Model evaluation and feature importance analysis
- Retention-oriented business interpretation

The complementary API repository extends the modeling workflow with:

- FastAPI REST service
- Pydantic input validation
- Scikit-learn Pipeline inference
- Model serialization with Joblib
- Automated tests with Pytest
- Docker and Docker Compose
- Interactive Swagger documentation

Together, the two repositories demonstrate the progression from:

Data preparation → Modeling → Evaluation → API → Testing → Containerization

## Causal Inference & Experimentation

A project focused on measuring incremental effects and comparing experimental and observational approaches.

The project includes:

- A/B testing and randomized experiment analysis
- Average Treatment Effect estimation
- Confidence intervals and statistical inference
- Propensity Score Matching
- Inverse Probability Weighting
- Double Machine Learning
- Conditional Average Treatment Effect estimation
- Causal Forest modeling
- Treatment effect heterogeneity
- Incrementality-oriented marketing analysis
- Comparison of experimental, observational, and machine-learning-based estimates

The project emphasizes the importance of assumptions, identification, diagnostics, uncertainty, and the distinction between prediction and causal inference.

## GBIF Amphibian Data Platform and Analysis

A combined data engineering and analytical workflow using biodiversity data from GBIF.

### ETL component

- SQL-based data ingestion and transformation
- Large-scale data cleaning
- Schema normalization
- Regex-based standardization
- Feature engineering
- Data quality assessment

### Analytical component

- Exploratory Data Analysis
- Spatial analysis
- Temporal trend analysis
- Poisson GLM regression
- Species accumulation curves
- Rarefaction analysis
- Sampling bias detection
- Interactive Plotly visualizations

This project demonstrates the application of reproducible data workflows and statistical analysis to heterogeneous observational data.

## Brazilian Anuran Biodiversity Dashboard

An interactive Power BI dashboard for exploring Brazilian anuran biodiversity data.

The dashboard includes:

- Executive KPIs
- Taxonomic diversity analysis
- Geographic analysis
- Temporal analysis
- Interactive filtering
- Business-style dashboard design

## NYC Taxi Data Engineering Platform

An end-to-end lakehouse and data engineering project built with Databricks, PySpark, and Delta Lake.

The pipeline processes more than **38 million NYC Yellow Taxi trips** using:

- Medallion Architecture
- Bronze, Silver, and Gold layers
- Incremental monthly processing
- Delta Lake storage
- Data quality validation
- Referential integrity checks
- Dimensional analytical modeling
- Fact and dimension tables
- Reusable analytical Gold tables

### Architecture

Raw Parquet → Bronze → Silver → Gold → Analytics

This project is included as a supporting project because it demonstrates scalable data processing and analytical data preparation rather than being a primary machine learning case.

[View the project repository](#)

## Meu Placar — Sports Analytics Dashboard

An interactive web application for football performance analytics, including:

- KPI dashboards
- Time-series analysis
- Historical performance tracking
- Data visualization
- Progressive Web App functionality

[View the project repository](#)

## Scientific Data Science Projects

These repositories document the application of statistical modeling, multivariate analysis, machine learning, and reproducible scientific workflows to biological data.

| Project | Main techniques |
|---|---|
| Pseudopaludicola coracoralinae | Random Forest, feature importance, statistical analysis |
| Pseudopaludicola matuta | Random Forest, permutation statistics, multivariate analysis |
| Pseudopaludicola florencei | Multiclass classification, machine learning |
| A New Charismatic Monkey Frog | Statistical modeling, morphometrics, machine learning |

## Skills and Technologies

### Analytics and Business Intelligence

- Business Intelligence
- Analytics Engineering
- Customer Analytics
- Customer Segmentation
- Customer Lifetime Value
- KPI Design
- Dashboard Development
- Data Visualization
- Business Storytelling
- SQL Analytics
- Data Modeling
- Star Schema
- Semantic Layer Design
- ETL Pipelines

### Statistics and Data Science

- Exploratory Data Analysis
- Statistical Inference
- Hypothesis Testing
- A/B Testing
- Causal Inference
- Treatment Effect Estimation
- Propensity Score Methods
- Double Machine Learning
- Causal Forests
- Incrementality Analysis
- Parametric and Non-parametric Statistics
- Permutation Tests
- Multivariate Analysis
- Classification
- Regression
- Feature Engineering
- Predictive Modeling
- Time-Series Forecasting
- Ensemble Learning
- Model Evaluation
- Model Interpretation

### Tools and Technologies

- Python
- SQL
- R
- PostgreSQL
- Power BI
- DAX
- Power Query (M)
- Pandas
- Scikit-learn
- XGBoost
- PySpark
- Databricks
- Delta Lake
- Parquet
- FastAPI
- Pydantic
- Docker
- Docker Compose
- Pytest
- Joblib
- Jupyter Notebook
- Git
- GitHub
- Excel
- DBeaver

## Selected Achievements

- 28 peer-reviewed scientific publications
- Participation in the description of 13 new amphibian species
- More than 10 years working with complex quantitative datasets
- Experience combining scientific research, statistical analysis, and business analytics
- Extensive experience with reproducible analytical workflows

## Contact

- [GitHub](#)
- [LinkedIn](#)

















# Data Analytics Portfolio

Welcome!

I'm **Felipe Andrade**, a **Data Analyst** and **PhD** with over 10 years of experience transforming complex real-world datasets into actionable insights through SQL, Python, Power BI, statistics, and machine learning.

My background in scientific research has strengthened my analytical thinking, hypothesis-driven problem solving, and ability to design reproducible analytical workflows. Today, I apply these same skills to solve business problems in customer analytics, business intelligence, and data visualization.

This repository serves as an index of my main data analytics projects, covering Business Intelligence, Analytics Engineering, Machine Learning, Statistical Analysis, and Scientific Data Science.

My portfolio demonstrates an end-to-end analytical workflow, from data engineering and SQL-based analytical modeling to customer insights, visualization, and statistical analysis.

I also develop data engineering solutions using distributed processing and lakehouse architectures, with a focus on scalable ingestion, data quality, incremental pipelines, and analytical data modeling.

---

# Technical Skills

### Analytics & Business Intelligence

* Business Intelligence (BI)
* Analytics Engineering
* Customer Analytics
* Customer Segmentation
* Customer Lifetime Value (CLV)
* KPI Design
* Dashboard Development
* Business Storytelling
* Data Visualization
* SQL Analytics
* Data Modeling
* Star Schema
* Semantic Layer Design
* ETL Pipelines

### Statistics & Machine Learning

* Exploratory Data Analysis (EDA)
* Statistical Inference
* Hypothesis Testing
* A/B Testing
* Causal Inference
* Treatment Effect Estimation
* Average Treatment Effect (ATE)
* Conditional Average Treatment Effect (CATE)
* Propensity Score Matching (PSM)
* Inverse Probability Weighting (IPW)
* Double Machine Learning (DML)
* Causal Forest
* Incrementality Analysis
* Parametric & Non-Parametric Statistics
* Permutation Tests
* Multivariate Analysis
* Random Forest
* Classification Models
* Feature Importance Analysis
* Predictive Modeling
* Time Series Forecasting
* Regression Models
* Ensemble Learning
* XGBoost
* Model Evaluation (MAE, RMSE, R²)
* Temporal Feature Engineering
* Model Deployment
* REST APIs for Machine Learning
* FastAPI
* Docker
* Docker Compose
* Model Serialization

---

# Tools & Technologies

* PostgreSQL
* SQL
* Power BI
* DAX
* Power Query (M)
* Python
* R
* Git
* GitHub
* Excel
* DBeaver
* Scikit-learn
* XGBoost
* Pandas
* Jupyter Notebook
* FastAPI
* Pydantic
* Docker
* Docker Compose
* Pytest
* Joblib
* PySpark
* Databricks
* Delta Lake
* Parquet


---

# ⭐ Featured Business Analytics Projects

These projects demonstrate my ability to solve business problems using modern analytics workflows.

| Project | Domain | Technologies |
| ----------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------- | ------------------------------------------------------------------ |
| **[Customer Analytics for Brazilian E-commerce](https://github.com/felipeandrade91/Customer-Analytics-for-Brazilian-E-commerce)** | Customer Analytics, Business Intelligence | PostgreSQL, SQL, Power BI, DAX, Star Schema, Analytics Engineering |
| **[NYC Taxi Data Engineering Platform](https://github.com/felipeandrade91/nyc-taxi-data-engineering)** | Data Engineering, Lakehouse Architecture | Databricks, PySpark, Delta Lake, Python, SQL, Medallion Architecture, Incremental Processing |
| **[Customer Segmentation & Customer Lifetime Value Analytics](https://github.com/felipeandrade91/customer-segmentation-clv)** | Customer Analytics, Customer Intelligence | PostgreSQL, SQL, Python, Pandas, Matplotlib, RFM, CLV |
| **[Customer Churn Prediction](https://github.com/felipeandrade91/customer-churn-prediction)** | Machine Learning, Customer Analytics | PostgreSQL, SQL, Python, Scikit-learn, XGBoost, Predictive Modeling, Classification |
| **[Customer Churn Prediction API](https://github.com/felipeandrade91/customer-churn-api)** | Machine Learning Deployment, API Development | Python, FastAPI, Scikit-learn, Pydantic, Docker, Docker Compose, Pytest |
| **[Causal Inference & Experimentation](https://github.com/felipeandrade91/causal-inference-experimentation)** | Causal Inference, Experimentation, Marketing Analytics | Python, A/B Testing, PSM, IPW, Double Machine Learning, Causal Forest, EconML |
| **[Sales Forecasting with Machine Learning - Rossmann Stores](https://github.com/felipeandrade91/sales-forecasting-rossmann)** | Machine Learning, Time Series Forecasting, Retail Analytics | PostgreSQL, Python, Pandas, Scikit-learn, XGBoost, Feature Engineering |
| **[GBIF Amphibian Data Pipeline](https://github.com/felipeandrade91/gbif-amphibians-etl-pipeline)** | Data Engineering | PostgreSQL, SQL, ETL |
| **[GBIF Amphibian Data Analysis](https://github.com/felipeandrade91/GBIF-Brazilian-Amphibian-Biodiversity-Analysis)** | Exploratory Data Analysis | Python, Pandas, Plotly |
| **[Brazilian Anuran Biodiversity Dashboard](https://github.com/felipeandrade91/Brazilian-Anuran-Diversity-Dashboard)** | Business Intelligence | Power BI, DAX |
| **[Meu Placar – Sports Analytics Dashboard](https://github.com/felipeandrade91/meuplacar)** | Sports Analytics | Power BI Concepts, KPI Design, Low-code |

---

# Scientific Data Science Projects

These repositories demonstrate the application of statistical modeling and machine learning to real-world biological datasets.

| Project                                                                                                 | Main Techniques                                              |
| ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| **[Pseudopaludicola coracoralinae](https://github.com/felipeandrade91/Pseudopaludicola-coracoralinae)** | Random Forest, Feature Importance, Statistical Analysis      |
| **[Pseudopaludicola matuta](https://github.com/felipeandrade91/Pseudopaludicola-matuta)**               | Random Forest, Permutation Statistics, Multivariate Analysis |
| **[Pseudopaludicola florencei](https://github.com/felipeandrade91/Pseudopaludicola-florencei)**         | Multi-Class Classification, Machine Learning                 |
| **[A New Charismatic Monkey Frog](https://github.com/felipeandrade91/A-new-charismatic-monkey-frog)**   | Statistical Modeling, Morphometrics, Machine Learning        |

---

# Project Highlights

## ⭐ Customer Analytics for Brazilian E-commerce

**Repository**

https://github.com/felipeandrade91/Customer-Analytics-for-Brazilian-E-commerce

### Highlights

* End-to-end Analytics Engineering workflow
* PostgreSQL analytical database
* SQL semantic layer
* Star Schema implementation
* Business-oriented SQL views
* Data quality validation
* Interactive Power BI dashboard
* Customer Analytics
* Sales Performance Analysis
* Logistics Performance Analysis
* Customer Satisfaction Analysis

---

## ⭐ NYC Taxi Data Engineering Platform

**Repository**

https://github.com/felipeandrade91/nyc-taxi-data-engineering

### Highlights

* End-to-end Data Engineering pipeline
* Databricks and PySpark distributed processing
* Medallion Architecture (Bronze, Silver and Gold)
* Delta Lake data storage
* Incremental monthly data processing
* Data quality validation and monitoring
* Dimensional data modeling
* Fact and dimension tables
* Referential integrity validation
* Analytical data layer
* Processing of 38+ million NYC Yellow Taxi trips

### Architecture

**Raw Parquet → Bronze → Silver → Gold → Analytics**

The project demonstrates the progression from raw data ingestion to validated analytical datasets, with incremental processing and data quality controls applied throughout the pipeline.

The analytical layer provides reusable Gold tables for downstream SQL analysis and BI workloads.

---

## ⭐ Customer Segmentation & Customer Lifetime Value Analytics

**Repository**

https://github.com/felipeandrade91/customer-segmentation-clv

### Highlights

* Customer-level analytical feature engineering
* RFM customer segmentation
* Historical Customer Lifetime Value (CLV) analysis
* Revenue concentration analysis
* Customer value distribution analysis
* PostgreSQL analytical workflows
* Python-based analytical visualization
* Business-oriented customer insights

### Relationship with previous project

This project extends the analytical foundation developed in:

**Customer Analytics for Brazilian E-commerce**

While the previous project focused on building an Analytics Engineering and Business Intelligence environment, this project applies customer intelligence techniques to transform transactional data into customer-level insights.

---

## ⭐ Customer Churn Prediction

**Repository**

https://github.com/felipeandrade91/customer-churn-prediction

### Highlights
* End-to-end Machine Learning workflow
* PostgreSQL-based data preparation
* SQL data quality validation
* Feature engineering and analytical dataset construction
* Exploratory Data Analysis (EDA)
* Statistical feature evaluation
* Customer churn classification models
* Logistic Regression, Random Forest and XGBoost evaluation
* ROC-AUC based model comparison
* Feature importance analysis
* Business-oriented churn insights and retention recommendations

---

## ⭐ Customer Churn Prediction API

**Repository**

https://github.com/felipeandrade91/customer-churn-api

### Highlights

* Machine Learning model deployment
* REST API development with FastAPI
* Pydantic-based input validation
* Scikit-learn Pipeline inference
* Model serialization with Joblib
* Automated API testing with Pytest
* Docker containerization
* Docker Compose deployment
* Interactive API documentation with Swagger UI
* Production-oriented API architecture

### Relationship with previous project

This project extends the machine learning workflow developed in:

**Customer Churn Prediction**

While the previous project focuses on data preparation, exploratory analysis, feature engineering, model development and evaluation, this repository focuses on deploying the trained model as a containerized REST API.

Together, the two projects demonstrate the progression from:

**Machine Learning → Model Deployment → REST API → Containerization**

---

## ⭐ Causal Inference & Experimentation

**Repository**

https://github.com/felipeandrade91/causal-inference-experimentation

### Highlights

* A/B Testing and randomized experiment analysis
* Average Treatment Effect (ATE) estimation
* Statistical inference and confidence intervals
* Propensity Score Matching (PSM)
* Inverse Probability Weighting (IPW)
* Double Machine Learning (DML)
* Conditional Average Treatment Effect (CATE)
* Causal Forest modeling
* Treatment effect heterogeneity analysis
* Incrementality-focused marketing analysis
* Comparison of experimental, observational and Machine Learning-based causal estimates

---

## ⭐ Sales Forecasting with Machine Learning - Rossmann Stores

**Repository**

https://github.com/felipeandrade91/sales-forecasting-rossmann

### Highlights

* End-to-end Machine Learning workflow
* PostgreSQL-based data preparation
* Exploratory Time Series Analysis
* Temporal feature engineering
* Lag feature creation
* Rolling window features
* Regression modeling for sales prediction
* Linear Regression, Random Forest and XGBoost evaluation
* Model comparison using MAE, RMSE and R²
* Feature importance analysis
* Prediction performance evaluation
* Retail-oriented forecasting insights

### Final Model Performance

The final XGBoost model achieved:

* MAE: 530.89
* RMSE: 822.87
* R²: 0.954

The model successfully captured historical sales patterns and business-related factors, demonstrating the application of machine learning for retail demand forecasting.

---

## GBIF Amphibian Data Pipeline

**Repository**

https://github.com/felipeandrade91/gbif-amphibians-etl-pipeline

### Highlights

* SQL ETL Pipeline
* Large-scale Data Cleaning
* Schema Normalization
* Regex-based Standardization
* Feature Engineering
* Data Quality Assessment

---

## GBIF Amphibian Data Analysis (Python)

**Repository**

https://github.com/felipeandrade91/GBIF-Brazilian-Amphibian-Biodiversity-Analysis

### Highlights

* Exploratory Data Analysis (EDA)
* Spatial Analysis
* Temporal Trend Analysis
* Poisson GLM Regression
* Species Accumulation Curves
* Rarefaction Analysis
* Sampling Bias Detection
* Interactive Plotly Visualizations

---

## Brazilian Anuran Biodiversity Dashboard

Interactive dashboard developed in Power BI.

### Highlights

* Executive KPIs
* Taxonomic Diversity
* Geographic Analysis
* Temporal Analysis
* Interactive Filtering
* Business-style Dashboard Design

---

## Meu Placar – Sports Analytics Dashboard

Interactive web application for football performance analytics.

### Highlights

* KPI Dashboard
* Time-series Analysis
* Historical Performance Tracking
* Data Visualization
* Progressive Web App (PWA)

---

# Selected Achievements

* 28 peer-reviewed scientific publications
* Description of 13 new amphibian species
* More than 15 years working with complex real-world datasets
* Extensive experience in reproducible analytical workflows
* Strong analytical background combining scientific research and business analytics

---

# Connect

* **GitHub:** https://github.com/felipeandrade91
* **LinkedIn:** https://linkedin.com/in/felipeandrade91
