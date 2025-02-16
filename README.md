# Data Science Assignment: eCommerce Transactions Dataset

## Overview

This repository contains the solutions for the **Data Science Assignment** based on an eCommerce Transactions dataset.  
The assignment focuses on deriving actionable insights and building models to understand customer behavior better.  
The tasks involve data analysis, predictive modeling, and customer segmentation.  

The assignment is divided into three primary tasks:

1. **Exploratory Data Analysis (EDA)** for uncovering business insights.  
2. **Lookalike Model** to recommend similar customers based on profiles and transaction patterns.  
3. **Customer Segmentation** using clustering algorithms to categorize customer behavior.

---

## Tasks Completed

### Task 1: Exploratory Data Analysis (EDA) and Insights
For this task, I performed comprehensive exploratory data analysis to identify trends, patterns, and key business insights.  

Key findings include:  
- **Geographic Distribution**: The South America region accounts for the highest percentage of customers (29.5%).  
- **Seasonal Patterns**: January has the highest transaction volume, while November has the least.  
- **Spending Trends**: Customers spend the most in April (average $290.46) and the least in March (average $224.60).  

More detailed insights are documented in the report `Tushar_Kumar_Shah_EDA.pdf`.  
The code for the analysis is available in `Tushar_Kumar_Shah_EDA.ipynb`.

---

### Task 2: Lookalike Model
In this task, I developed a Lookalike Model to identify similar customers based on transaction history and profile data.  
The model uses a similarity score to recommend the top 3 customers most similar to each user.

The recommendations and similarity scores are saved in `Tushar_Kumar_Shah_Lookalike.csv`.  
Details of the methodology and implementation are explained in `Tushar_Kumar_Shah_Lookalike.ipynb`.

---

### Task 3: Customer Segmentation
This task focused on clustering customers based on behavioral data. I applied the KMeans clustering algorithm and evaluated the results using the **DB Index**.  
Clusters were visualized to understand distinct customer groups and their characteristics.

The detailed clustering report is in `Tushar_Kumar_Shah_Clustering.pdf`.  
The implementation code is available in `Tushar_Kumar_Shah_Clustering.ipynb`.

---

## Repository Structure

```plaintext
├── Tushar_Kumar_Shah_EDA.ipynb               # Jupyter notebook for EDA and insights  
├── Tushar_Kumar_Shah_EDA.pdf                 # PDF report with EDA insights and findings  
├── Tushar_Kumar_Shah_Lookalike.ipynb         # Notebook for Lookalike Model development  
├── Tushar_Kumar_Shah_Lookalike.csv           # CSV with top 3 lookalike customers and similarity scores  
├── Tushar_Kumar_Shah_Clustering.ipynb        # Notebook for clustering implementation and visualization  
├── Tushar_Kumar_Shah_Clustering.pdf          # PDF report with clustering analysis  
├── README.md                                 # This README file  
