# 🚴‍♂️ Bike Sales Lakehouse — End to En Databricks Project
&nbsp;&nbsp;&nbsp;This repository contains a complete, real-world Data Lakehouse implementation built on Databricks, including datasets, notebooks, SQL examples, and exercises. 
The objective was to build a production-ready data platform that ingests raw CRM and ERP data, transforms it through a Medallion Architecture, and delivers analytics-ready datasets optimized for BI and reporting.

&nbsp;
&nbsp;

## 🛠️ Tools and Platforms :

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-FDEE21?style=flat&logo=apachespark&logoColor=black)
![CSV](https://img.shields.io/badge/CSV-%2300B22D.svg?style=flat&logo=csv&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-003366?style=flat&logo=databricks&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=flat&logo=postgresql&logoColor=white)
![Medallion Architecture](https://img.shields.io/badge/Architecture-Medallion-blue)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-%232671E5.svg?style=flat&logo=github-actions&logoColor=white)
&nbsp;

&nbsp;
## 🏗️ Architecture Overview
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
&nbsp;

&nbsp;
<img width="1411" height="782" alt="Bike Data Lakehouse drawio" src="https://github.com/user-attachments/assets/dd6d9738-409a-4833-905b-0c50ebefa880" />
&nbsp;

🥉 **Bronze Layer** : Raw Data Ingestion
The Bronze layer is responsible for ingesting raw CRM and ERP data into Delta tables with minimal transformation. Data is stored in its original structure to preserve lineage and historical traceability. 

**🥈 Silver Layer :** Data Cleaning and Standardization
The Silver layer transforms raw Bronze data into structured, validated datasets. During this stage, data types are enforced, null values are handled, categorical values are standardized, and business keys are parsed and normalized.

**🥇 Gold Layer** : Dimensional Modeling
The Gold layer represents the business consumption layer. Here, the cleaned Silver data is transformed into a star schema composed of dimension tables and a central fact table.
&nbsp;

&nbsp;
<img width="1241" height="821" alt="Bike Lakehouse Data Flow drawio" src="https://github.com/user-attachments/assets/7a8fa1d6-2b1f-4520-becf-6a15ce61453e" />
&nbsp;

&nbsp;
## 🧭 Data Modeling Stage :
After ensuring that all datasets were cleaned and standardized in the Silver layer, the next objective was to structure the data in a way that supports efficient analytics and intuitive reporting. For this purpose, a dimensional modeling approach was adopted, specifically a star schema.
&nbsp;

&nbsp;
<img width="1401" height="912" alt="Bike Data Lakehouse Integration Model drawio" src="https://github.com/user-attachments/assets/490851bb-e91c-4a51-8ea6-ac5f37cf797f" />

&nbsp;

&nbsp;

## 🚦Pipeline Orchestration : 

To ensure structured execution, orchestration notebooks were implemented for each layer. Each orchestration notebook acts as a single entry point, validating dependencies and executing transformations in the correct order.
&nbsp;

&nbsp;
<img width="1042" height="402" alt="Bike Data Lakehouse Pipeline" src="https://github.com/user-attachments/assets/4f1f2209-0ae6-4049-8ecd-330bf5aa03d4" />

## 📋 Conclusion

This project showcases the complete lifecycle of building a modern Lakehouse platform, from raw data ingestion to business-ready analytics. It reflects real-world data engineering practices including layered architecture design, dimensional modeling, workflow orchestration, and production automation.

The final result is a scalable, structured, and production-ready data platform built using Databricks and Delta Lake


## 🧑‍💻 About Me
&nbsp;&nbsp;&nbsp; I’m a passionate data enthusiast eager to expand my expertise beyond analytics into data engineering. This portfolio showcases my journey into the world of data warehousing, where I design ETL pipelines, build dimensional models, and integrate multiple data sources to create centralized repositories for analytics and reporting.

Thank you for visiting my Data Analysis Portfolio! I hope you find my projects informative and insightful.
&nbsp;

&nbsp;
## 🌐 For Contact and Business:

If you have any questions, feedback, or collaboration opportunities, please feel free to reach out to me. 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/www.linkedin.com/in/mohammed-herradi) 
[![Upwork](https://img.shields.io/badge/Upwork-%2300A3EC.svg?logo=upwork&logoColor=white)](https://www.upwork.com/) 
[![Fiverr](https://img.shields.io/badge/Fiverr-%2300B22D.svg?logo=fiverr&logoColor=white)](https://www.fiverr.com/)
