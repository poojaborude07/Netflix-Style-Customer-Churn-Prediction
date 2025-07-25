# Netflix-Style-Customer-Churn-Prediction

This project aims to **predict customer churn** for a subscription-based streaming service using **machine learning models**. By analyzing user behavior and account details, the system helps the business **proactively identify customers at risk of leaving**, enabling better retention strategies.

 **Notebook Includes**:

Simulated dataset creation (1,000 users)

EDA (plots & summaries)

Preprocessing (scaling, encoding)

Model training (Logistic Regression, Random Forest, Gradient Boosting)

Evaluation (Confusion Matrix, ROC AUC, Reports)

Hyperparameter Tuning

Model Saving

---

#  Project Motivation

In today's competitive streaming market, customer retention is more cost-effective than acquiring new users. Predicting churn lets companies take timely actions — like offering discounts or improving support — to keep valuable users engaged.
# For Example - How a Company Can Use This Model After Training

 Let’s imagine you're a Netflix user. Here's how it works:

 You (the customer) are using the app. Behind the scenes, the app records:
Age: 28

Gender: Female

Subscription Type: Standard

Monthly Charges: ₹499

Subscription Length: 8 months

Viewing Hours per Week: 3.2

Content Downloads/Month: 1

Genre Preference: Drama

User Rating: 3.9

Multi-Device Access: Yes

Number of Profiles: 3

Support Tickets Raised: 1

Days Since Last Login: 25

- These inputs go into the trained ML model:
  
  model.predict([your_data])

 # Output:
 
0 → Not likely to churn

1 → At risk of churning

# How the company uses this:
If you're predicted as “1: Churn”, they could:

Send you a retention offer (discount, free upgrade)

Email personalized content suggestions

Call you or notify via app for re-engagement

This lets companies take action before customers actually leave.



---
