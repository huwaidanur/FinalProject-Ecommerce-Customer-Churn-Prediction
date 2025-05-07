# Customer Churn Prediction 

## Introduction
Customer retention is a critical challenge for e-commerce businesses. Losing customers (*churn*) not only decreases revenue but also raises marketing expenses for acquiring new users. Since **customer retention cost (CRC)** is typically lower than **customer acquisition cost (CAC)**, implementing an effective churn mitigation strategy is essential for long-term business growth.

## Problem Statement
The goal of this project is to **predict customer churn** so that:
1. **The company can proactively retain high-value customers** before they leave the platform.
2. **Revenue can be optimized** by reducing churn and improving customer engagement.

## Machine Learning Objective
This project aims to develop a **predictive model** to:
- **Minimize revenue loss** by identifying at-risk customers early.
- **Enhance retention efforts** through data-driven insights.

Using data science, we can:
- **Predict customers likely to churn** and take preventive measures.
- **Identify key factors influencing churn**, helping refine retention strategies.

A data-driven approach allows businesses to **optimize retention strategies** and **mitigate the financial impact of churn**.

## Analytical Approach
This project involves:
1. **Exploratory Data Analysis (EDA)** to identify churn patterns.
2. **Building supervised learning models (classification)** to:
   - Predict the probability of customer churn.
   - Identify the most influential churn factors using feature importance analysis.

## Business Value Proposition
Implementing a churn prediction model provides tangible benefits, including:

### 1. Increased Revenue & Cost Efficiency
- **Reduces revenue loss** by proactively retaining customers.
- **Decreases marketing costs** by focusing on retention rather than acquisition.

### 2. Improved Retention Strategies
- **Helps businesses develop targeted interventions** for high-risk customers.
- **Enhances customer loyalty**, ensuring a stable revenue stream.

## Performance Metrics
For churn prediction, choosing the right evaluation metric is crucial. The **confusion matrix** offers detailed insights into model performance by breaking down actual vs. predicted outcomes.

### Key Considerations
#### 1. False Negatives (Type II Error)
- When the model fails to identify actual churners.
- **Impact:**
  - **Revenue loss** from customers who leave.
  - **Increased acquisition costs** to replace lost users.
- **Solution:**
  - **Improve recall** to detect more potential churners.

#### 2. False Positives (Type I Error)
- When the model incorrectly classifies loyal customers as churners.
- **Impact:**
  - **Unnecessary retention costs** for customers unlikely to churn.
  - **Potential negative customer experience** due to unnecessary interventions.
- **Solution:**
  - Balance recall and precision by optimizing the **F1 Score**.

### Why Use F1 Score?
Since churn prediction requires both **high recall (capturing actual churners)** and **high precision (avoiding false churn predictions)**, the **F1 Score** is the best metric. It balances recall and precision, ensuring accurate detection of churners while minimizing retention costs. This results in a **cost-effective and efficient churn reduction strategy**.

## Conclusion
By leveraging machine learning for churn prediction, businesses can:
- **Make informed, data-driven decisions** to reduce customer attrition.
- **Implement targeted retention strategies** to maximize customer lifetime value.
- **Optimize costs and improve profitability**, leading to sustainable business growth.
___
![Screenshot 2025-02-26 230530](https://github.com/user-attachments/assets/9e814ab7-0f69-4bda-aa27-e229372ddbc3)

![Screenshot 2025-02-26 230750](https://github.com/user-attachments/assets/2c1850a7-14a1-4a80-8f2e-caf7564c775d)

Tableau link : https://public.tableau.com/app/profile/huwaida.nur.asysyifa.mufarrida/viz/customerprofile_17405067669130/EcommerceCustomerChurnAnalysis?publish=yes
