# 🚗 Vehicle Collision Analysis on Databricks

This repository contains the code and documentation for the **Vehicle Collision Analysis on Databricks** project, which focuses on exploring the complex relationships between environmental factors and vehicle collisions using data analysis and machine learning techniques.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)  
- [Objectives](#objectives)  
- [Dataset](#dataset)  
- [Methodology](#methodology)  
- [Models and Evaluation](#models-and-evaluation)  
- [Prerequisites](#prerequisites)  
- [Installation](#installation)  
- [Running the Analysis](#running-the-analysis)  
- [Team](#team)  


---

## 🧠 Project Overview

Traffic authorities and urban planners worldwide are concerned about vehicle crashes. While driver behavior and vehicle condition are often cited as causes, environmental factors such as **weather, lighting, and road surface conditions** also play a crucial, often overlooked, role.

This project, titled **"The Role of Environmental Conditions in Vehicle Collisions: Insights from Data"**, investigates these complex relationships to assess the direct and indirect impact of varying environmental conditions on vehicle accidents using the Databricks platform.

---

## 🎯 Objectives

- **Assessment of Environmental Factors:** Identify and evaluate environmental conditions (e.g., weather, lighting, road surface) that significantly influence the occurrence and severity of vehicle collisions.
- **Data Gathering & Analysis:** Collect, clean, and analyze a comprehensive dataset related to vehicle accidents and environmental parameters.
- **Predictive Modeling:** Build a logistic regression model to classify accident severity based on environmental and other contextual variables.

---

## 📊 Dataset

- **Source:** [Motor Vehicle Collisions - Crashes](https://data.cityofnewyork.us/)
- **File Used:** `collision_data_new-2.csv`
- **Key Columns:**
  - `CRASH DATE`, `CRASH TIME`, `BOROUGH`, `ZIP CODE`, `LATITUDE`, `LONGITUDE`
  - `NUMBER OF PERSONS INJURED`, `NUMBER OF PERSONS KILLED`
  - `LIGHTING_CONDITION`, `HOUR_OF_DAY`, `SEVERITY`, `accident_severity`
  - `CONTRIBUTING FACTOR VEHICLE 1–5`, `VEHICLE TYPE CODE 1–5`

---

## 🛠️ Methodology

1. **Data Preprocessing**
   - Parsed and casted columns to appropriate data types.
   - Cleaned missing or inconsistent values.
  
2. **Exploratory Data Analysis (EDA)**
   - Identified patterns and correlations in crash severity vs. lighting, time of day, and road conditions.

3. **Model Training**
   - Applied **Logistic Regression** to predict the severity of collisions.
  
4. **Evaluation Metrics**
   - ROC-AUC, Precision, Recall, and Accuracy.

---

## 🤖 Models and Evaluation

- **Model Used:** Logistic Regression (binary classification for accident severity)
- **Evaluation Metrics:**
  - Area Under the ROC Curve (ROC-AUC)
  - Accuracy
  - Precision
  - Recall

---

## 🧰 Prerequisites

Before getting started, ensure the following:

- A working [Databricks](https://databricks.com/) account
- Basic knowledge of **Apache Spark** and **Databricks Notebooks**
- Access to the `collision_data_new-2.csv` dataset

---

## ⚙️ Installation

1. Log in to your Databricks workspace.
2. Import the following notebooks and scripts:
   - `Final_project_AIT614.ipynb`
   - `Final_Project_AIT614.py`

---

## ▶️ Running the Analysis

1. Upload the dataset (`collision_data_new-2.csv`) to DBFS or mount cloud storage.
2. Update the file path in the notebook to match your data source.
3. Open the notebook in Databricks.
4. Run each cell in order and observe the visualizations and output metrics.
5. Modify parameters or features as needed for experimentation.

---

## 👥 Team

- **Shashank Yelagandula** 
- **Akhil Reddy Chimmula** 
- **Bhavesh Kurella** 
- **Bhuvana Yadavalli** 

---

## 📬 Contact

For questions or suggestions, feel free to contact:

---

## 📄 License

This project is for academic purposes only.  
Licensed under: **MIT License**  

---
