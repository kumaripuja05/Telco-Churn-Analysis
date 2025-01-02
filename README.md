# Telco-Churn-Analysis


## **Table of Content**
   - [Project Overview](#project-overview)
   - [Objectives](#objectives)
   - [Data Sources Overview](#data-sources-overview)
   - [Tools](#tools)
   - [Features](#features)
   - [Data Analysis with Python](#data-analysis-with-python)
   - [Chart Overview](#chart-overview)
   - [Results](#results)
   - [Key Recommendations](#key-recommendations)

     
## **Project Overview**

Customer churn is a critical challenge for businesses, especially in the telecom industry. This project aims to analyze churn patterns using a telecom customer dataset to uncover actionable insights. By leveraging Python for data cleaning, visualization, and analysis, the project identifies factors contributing to churn and suggests strategies to improve customer retention.

## **Objectives**
 - Analyze customer churn trends and identify high-risk segments.
 - Investigate the relationship between customer demographics, service preferences, and churn behavior.
 - Provide actionable insights to improve customer retention strategies.


## Data Sources Overview

Churn data: The Primary dataset used for this analysis is the "Customer_Churn.csv" file., containing detailed information about customer demographics, account information, and service details. 

The dataset used in this analysis is focused on Telco Customer Churn, commonly sourced from public datasets or proprietary business data. Below is an overview of typical attributes in the dataset:

 - CustomerID: Unique identifier for each customer.
 - Gender: Gender of the customer (e.g., Male, Female).
 - SeniorCitizen: Whether the customer is a senior citizen (1: Yes, 0: No).
 - Partner/Dependents: Indicates if the customer has a partner or dependents.
 - Tenure: Number of months the customer has stayed with the company.
 - Services Signed Up: Includes Phone Service, Internet Service, Online Security, etc.
 - Contract Type: Customer's contract type (e.g., Month-to-Month, One-Year, Two-Year).
 - Payment Details: Payment method, monthly charges, total charges, etc.
 - Churn: Indicates whether the customer churned (Yes/No).

## Tools

**1. Python Libraries**
 -  Pandas:
     For data manipulation, cleaning, and exploratory analysis.
     Used to handle missing values, transform data, and calculate churn statistics.
 -  NumPy:
     For numerical operations and efficient handling of array-based data.
 -  Matplotlib:
     For creating static visualizations like bar charts, pie charts, and line plots.
 -  Seaborn:
     For creating aesthetically pleasing and informative visualizations such as heatmaps, pair plots, and box plots.

**2. Jupyter Notebook**
     - Served as the primary environment for coding and visualizing results interactively.

**3. Data Visualization Techniques**
  -  Pie Charts: To display the proportion of churned customers.
  -  Bar Charts: To compare churn rates across categories (e.g., contract types).
  -  Box Plots: To explore distributions and outliers for key variables like tenure and charges.

## **Features**

This repository provides the following key features for Telco Customer Churn analysis:

**Data Cleaning and Preprocessing:**

   - Handling missing values, such as replacing blanks with zeros.

   - Ensuring data types are consistent for analysis.

**Exploratory Data Analysis (EDA):**

   - Visualizing customer demographics, service usage, and churn trends.

   - Statistical summaries and distribution plots for key features.

**Churn Prediction Insights:**

  - Highlighting factors contributing to customer churn.

  - Creating visual representations of churn-related trends.

**Customizable Analysis:**

   - Flexible framework to add new data or features.

   - Modular code design for easy adaptation to other datasets.

  ## **Data Analysis with Python**

  The Telco Customer Churn analysis leverages Python for comprehensive data exploration and insights. Below are the key steps and techniques implemented in the notebook:

  #### **Data Cleaning:**

 -  Handling missing values, such as replacing blanks with zeros.

 -  Ensuring consistent data types for numerical and categorical fields.

  #### **Exploratory Data Analysis (EDA):**

 -  Descriptive Statistics: Summarizing central tendencies, dispersions, and distributions.

 -  Visualizations: Creating histograms, box plots, and correlation heatmaps to understand relationships and patterns.

  #### **Feature Engineering:**

 -  Transforming and encoding categorical variables for analysis.

 -  Creating new features, such as tenure groups or service usage clusters, for better insights.

  #### **Churn Analysis:**

  - Identifying key factors influencing churn through visualizations and statistical tests.

  - Segmenting customers based on churn likelihood and services used.

  #### **Visualization Tools:**

 - Matplotlib: For static visualizations, including bar plots and line charts.

 - Seaborn: For advanced and aesthetically pleasing plots, such as pairplots and heatmaps.

These steps provide a robust framework for analyzing customer churn and generating actionable insights for decision-making.

## **Chart Overview**

   This analysis employs various types of charts to effectively communicate insights:

 **1. **Bar Charts:****
To compare categorical data, such as churn rates across contract types or payment methods.

 **2. Histograms:**
To display the distribution of numerical variables like tenure and monthly charges.

 **3. Box Plots:**
To highlight variations in customer charges and detect outliers.

 **4. Heatmaps:**
To show correlations between numerical features and their relationship to churn.

 **5. Pie Charts:**
To illustrate proportions, such as the percentage of customers using specific services.

 **6. Scatter Plots:**
To analyze relationships between variables, like tenure and total charges.

  These charts provide a comprehensive view of customer behaviors, enabling a deeper understanding of factors driving churn.

  ![Screenshot 2024-12-26 214739](https://github.com/user-attachments/assets/f4000518-6ff7-43a7-b959-ca27bc0b9856)
![Screenshot 2025-01-02 203338](https://github.com/user-attachments/assets/4c7be7bd-ecbd-41c1-a3fc-54d9418ce9e6) ![Screenshot 2025-01-02 203426](https://github.com/user-attachments/assets/bc799b3e-96b9-4556-a64e-2e57e98143b3)



## **Results**

The Telco Customer Churn analysis revealed the following key insights:

 **1. Churn Rates:**

   Approximately 26% of customers in the dataset churned.

 **2. Key Factors Influencing Churn:**

   Customers with month-to-month contracts are more likely to churn compared to those with longer-term contracts.

   Higher monthly charges are associated with increased churn likelihood.

   Customers without additional services, such as online security or tech support, exhibit higher churn rates.

 **3. Service-Specific Trends:**

   Fiber optic internet users tend to churn more often than DSL users, possibly due to pricing or service issues.

   Customers who do not use streaming services (TV or movies) show a slightly lower churn rate.

 **4. Demographics:**

   Senior citizens have a higher churn rate compared to younger customers.

   Customers without dependents are more likely to churn.

 **5. Retention Strategies:**

   Offering discounts or incentives for customers on month-to-month contracts could reduce churn.

   Bundling services like online security and tech support may improve retention.

These results provide actionable insights for telecom companies to enhance customer retention strategies and reduce churn rates effectively.
 
   
## **Key Recommendations**
 - Retention Strategy for New Customers:
   Focus on improving the onboarding process for customers in their first few months.
   Implement targeted interventions, such as personalized offers or improved support.
 - Senior Citizen Engagement:
   Address concerns specific to senior citizens, including pricing flexibility and tailored support.
 - Contract Optimization:
   Promote long-term contracts with incentives to reduce churn among month-to-month customers.
 - Service Quality Enhancement:
   Investigate fiber optic service complaints to address dissatisfaction and improve retention.
