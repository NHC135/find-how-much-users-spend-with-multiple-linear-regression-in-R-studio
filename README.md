# About Dataset 
The dataset is found from from kaggle, an ecommerce dataset. This dataset is having data of customers who buys clothes online.
The store offers in-store style and clothing advice sessions.
Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.
The company is trying to decide whether to focus their efforts on their mobile app experience or their website.

# Multiple/Single Linear Regression Analysis in RStudio

This repository demonstrates the creation of a **linear regression model** in **RStudio**, including **modeling, evaluation, and visualization**.  
It showcases skills relevant to data analysis, statistical modeling, and reproducible research — highly applicable for data science roles.

---

## Overview

**Objective:** Predict a target variable based on one and multiple predictor(s) using **linear regression**.  

**Key Skills Demonstrated:**
- Exploratory Data Analysis 
- Building and evaluating linear regression models (`lm`)
- Model interpretation and visualization (`ggplot`)
- Reproducible workflow and code organization:
  https://www.notion.so/Single-Multiple-Linear-Regression-Model-in-R-Studio-w-Ecommerce-Data-2f5c513841c84ba7b43a7a48c8437043?source=copy_link

## **Analysis:**  
**Time on App** (Most Impactful)  
Coefficient: 38.71  
For every additional unit increase in time spent on the mobile app, annual spending increases by approximately $38.71, holding other factors constant.  
**Business implication:**  
Mobile app engagement is a major revenue lever.  
  
**Length of Membership**  
Coefficient: 61.58  
Each additional year (or unit) of membership increases annual spending by roughly $61.58.  
**Business implication:**  
Customer retention is critial.  
Loyalty programs and churn prevention strategies directly increase revenue.  
  
**Avg Session Length**  
Coefficient: 25.73  
Longer sessions are associated with higher annual spending (~$25.73 per unit increase).  
**Business implication:**   
Deeper engagement correlates with higher monetization.  
Content and personalization improvements could drive higher spend.

**Time on Website (Not Significant)**  
p-value = 0.326 (Not statistically significant)  
Time spent on the website does not significantly predict annual spending once mobile app usage and membership length are accounted for.  
**Business implication:**  
The company may be mobile-dominant.  
Website optimization may not produce meaningful revenue impact compared to app improvements.  
  
**Model Strength**  
R² = 0.984  
The model explains 98.4% of variation in annual spending  
Highly statistically significant overall (F-test p < 0.001)  
**Business translation:**
The model provides highly reliable estimates of spending behavior and can be used for forecasting and revenue planning.  
---

## 🛠 Tools & Packages

- **R & RStudio**
- **Packages:** `ggplot2`

## Visualizations: 
<img width="840" height="630" alt="Rplot06" src="https://github.com/user-attachments/assets/0a82b24a-9d98-4762-9ae3-11726f6ce362" />
<img width="840" height="630" alt="Rplot" src="https://github.com/user-attachments/assets/5374484e-31b3-440b-890f-71eb0d6fe71a" />
