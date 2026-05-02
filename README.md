# Predicting Employee Attrition in the Saudi Private Sector 🇸🇦📊

**Course:** ARTI 506 - Data Science and Analytics  
**Team:** Group 3  

## 📌 Project Overview
Employee turnover represents a critical operational and financial challenge for organizations. With the rapid economic expansion driven by **Saudi Vision 2030**, the private sector is experiencing a highly dynamic labor market. Retaining top talent is more critical than ever. 

This project utilizes a machine learning pipeline to predict employee attrition specifically within the Saudi private sector. By transitioning from reactive HR practices to proactive "People Analytics," this project identifies at-risk employees and extracts the key drivers behind employee turnover.

## 🗄️ Dataset
* **Source:** 2025 Mendeley "Saudi Employee Attrition" Dataset
* **Size:** 1,200 records (Private-sector employees)
* **Features:** 34 distinct attributes (Demographics, Job Satisfaction, Compensation, Work-Life Balance, etc.)
* **Target Variable:** `Attrition` (Binary: Yes/No)

## 📂 Repository Structure
```text
├── eda.ipynb                              # Exploratory Data Analysis & Visualizations
├── preprocessing.ipynb                    # Data cleaning, imputation, and encoding
├── enhanced_model.ipynb                   # Model training, GridSearch, and Feature Extraction
├── processed_dataset_tree.csv             # Cleaned data (Label Encoded)
├── processed_dataset_nontree.csv          # Cleaned data (One-Hot Encoded & Scaled)
└── model.ipynb                            # Model Implementation
