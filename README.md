# ECommerce Customer Churn Prediction 

## 📌 Context  
A company operating in the **e-commerce** industry is facing intense competition in retaining its customers. In this sector, **customer churn**—when customers stop purchasing from the platform—directly impacts revenue and increases the cost of acquiring new customers.

The company has collected various customer-related data, including purchase behavior, transaction frequency, payment methods, and demographic information. This data can be leveraged to gain deeper insights into churn patterns.

---

## Problem Statement  
Currently, the company does not have a predictive system to identify customers who are at risk of churning. Without such a system, the marketing or retention teams must target all customers equally, leading to:

- 💸 **Wasted retention costs**
- ⚠️ **Ineffective interventions**

Without a data-driven strategy, retention efforts are often inefficient and yield suboptimal results, as they fail to focus on customers who are actually at risk.

---

## Goals  
To address the challenges above, the company aims to develop a **machine learning-based predictive model** that can:

1. **Identify customers who are likely to churn**, so that retention efforts can be more focused.
2. **Reveal the key factors contributing to churn**, helping the team design more effective retention strategies.

This approach will enable the company to:

- Reduce unnecessary spending on retention
- Improve customer loyalty
- Maintain stable revenue growth

---

## Analytic Approach  
The steps taken in this project are as follows:

1. **Exploratory Data Analysis (EDA)**  
   Analyze historical customer data to identify patterns and distinguish between loyal customers and churners.

2. **Model Building**  
   Develop a **classification model** using machine learning to predict the likelihood of customer churn. The model will be evaluated primarily using the **F1 Score**, which balances **False Positives (FP)** and **False Negatives (FN)**.

3. **Business Interpretation**  
   Visualize the results in an **interactive dashboard** to help business teams interpret key insights and make data-driven decisions.

---

## Metric Evaluation
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
 
 ---
 
## Expected Outcome  
By leveraging this predictive model, the company will be able to:

- 🎯 Focus retention strategies on high-risk customers
- 🧠 Understand what drives churn in their customer base
- 💰 Reduce overall retention costs by avoiding unnecessary outreach to loyal customers
- 📉 Minimize the revenue loss caused by unexpected churn

---

## Project Structure  
- `notebooks/` : Jupyter notebooks for EDA and model building  
- `data/` : Raw and processed datasets (clean_data) 
- `models/` : Trained model files  
- `dashboard/` : Interactive dashboard (tableau)  
- `report/` : Final report and performance evaluation  

---

## Tech Stack  
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Tableau for dashboard
- Jupyter Notebook for experimentation and EDA

---

___
![Screenshot 2025-02-26 230530](https://github.com/user-attachments/assets/9e814ab7-0f69-4bda-aa27-e229372ddbc3)

![Screenshot 2025-02-26 230750](https://github.com/user-attachments/assets/2c1850a7-14a1-4a80-8f2e-caf7564c775d)

Tableau link : https://public.tableau.com/app/profile/huwaida.nur.asysyifa.mufarrida/viz/customerprofile_17405067669130/EcommerceCustomerChurnAnalysis?publish=yes
