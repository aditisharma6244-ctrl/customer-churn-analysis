# Customer Churn Analysis

## 📌 Project Overview

Customer churn refers to customers cancelling or discontinuing their subscriptions.

This project analyzes customer data to identify patterns associated with subscription cancellations. The analysis focuses on customer activity, engagement, satisfaction, subscription details, and behavioral trends to understand which factors are associated with higher churn.

The project uses Python and exploratory data analysis techniques to identify potential churn-risk patterns and suggest customer retention strategies.

---

## 🎯 Objectives

- Analyze the overall customer churn rate.
- Compare engagement levels between churned and retained customers.
- Study the relationship between monthly logins and churn.
- Analyze watch hours and customer activity.
- Examine customer satisfaction and churn patterns.
- Study the effect of subscription tenure.
- Analyze support ticket behavior.
- Compare churn across subscription types.
- Examine the relationship between auto-renewal and churn.
- Identify customers with different levels of potential churn risk.
- Suggest data-driven approaches for improving customer retention.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Jupyter Notebook

---

## 📂 Dataset

A synthetic customer dataset was created for this analysis.

The dataset contains **300 customer records** with the following attributes:

| Feature | Description |
|---|---|
| Customer_ID | Unique customer identifier |
| Subscription_Type | Basic, Standard, or Premium |
| Tenure_Months | Number of months the customer has subscribed |
| Monthly_Charge | Customer's monthly subscription charge |
| Monthly_Logins | Number of monthly logins |
| Support_Tickets | Number of support requests |
| Watch_Hours | Monthly content watch hours |
| Payment_Method | Customer payment method |
| Auto_Renewal | Whether automatic renewal is enabled |
| Satisfaction_Score | Customer satisfaction score from 1–10 |
| Churn | Whether the customer cancelled the subscription |

---

## 🔍 Analysis Performed

### 1. Overall Churn Analysis

The overall percentage of customers who churned was calculated to understand the scale of customer cancellations.

### 2. Engagement Analysis

Customer engagement was analyzed using:

- Monthly logins
- Watch hours
- Support tickets

These metrics were compared between churned and retained customers.

### 3. Satisfaction Analysis

Customer satisfaction scores were analyzed to identify differences between customers who churned and those who remained subscribed.

### 4. Tenure Analysis

Customer tenure was examined to identify whether newer or longer-term customers showed different churn patterns.

### 5. Subscription Analysis

Churn rates were compared across:

- Basic
- Standard
- Premium

subscription plans.

### 6. Auto-Renewal Analysis

Customers with and without automatic renewal were compared to identify differences in churn rates.

### 7. Engagement-Level Analysis

Customers were grouped into:

- Low engagement
- Medium engagement
- High engagement

based on monthly login activity.

### 8. Churn Risk Analysis

A simple risk score was created using behavioral indicators such as:

- Low monthly logins
- Low satisfaction
- No auto-renewal
- Short tenure
- High number of support tickets

Customers were categorized into Low, Medium, and High potential risk levels.

---

## 📊 Key Insights

The analysis is designed to identify patterns such as:

- Lower customer engagement being associated with higher churn.
- Lower satisfaction levels being associated with increased churn.
- Customers with shorter subscription tenure showing different churn behavior.
- Auto-renewal status being associated with customer retention.
- High support activity potentially indicating customer dissatisfaction.
- Higher-risk customer groups requiring additional retention attention.

> **Note:** These observations represent associations found in the dataset. They should not be interpreted as proof that a particular factor directly causes churn.

---

## 💡 Retention Recommendations

Based on the observed behavioral patterns, businesses could consider:

1. **Engagement campaigns**  
   Encourage inactive customers to return through personalized content and notifications.

2. **Early-stage customer support**  
   Monitor new customers and provide additional assistance during their first few months.

3. **Satisfaction monitoring**  
   Identify customers with low satisfaction scores and collect feedback before cancellation.

4. **Support-ticket follow-up**  
   Investigate repeated support requests and address recurring customer problems.

5. **Renewal reminders**  
   Encourage eligible customers to enable automatic renewal where appropriate.

6. **Targeted retention campaigns**  
   Use churn-risk indicators to identify customers who may benefit from personalized retention offers.

---

## 📁 Project Structure

```text
customer-churn-analysis/
│
├── Churn_Analysis.ipynb
├── customer_churn_raw.csv
├── customer_churn_analysis.csv
└── README.md
