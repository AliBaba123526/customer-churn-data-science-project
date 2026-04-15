# 01 Problem Definition

## 1. Problem Understanding

We are trying to predict which customers are likely to churn so the company can take action before they leave.

This matters because identifying at-risk customers early allows the business to reduce customer loss and protect revenue.

The company and its management care about this because customer churn directly impacts profit, and taking timely action can improve customer retention.

## 2. Decision Thinking

**Decision Maker:**  
The marketing or customer retention team responsible for customer engagement.

**Decision:**  
Which customers are most likely to churn and should be targeted for retention.

**Action:**  
Target high-risk customers with retention strategies such as discounts, personalised offers, or improved customer engagement.

**Outcome Variable (y):**  
Customer churn (Yes/No)

## 3. Initial Hypotheses

- **Age:** Different age groups may have different preferences, and the service may not appeal equally to all demographics.
- **Price / Charges:** Higher costs may lead customers to leave if they perceive the service as too expensive or not worth the value.
- **Service Quality:** Poor customer experience or dissatisfaction with the service may increase churn.
- **Usage Behaviour:** Customers who use the service less may be more likely to churn due to lack of engagement or perceived value.
- **User Experience:** Issues such as slow or unfriendly website/app interfaces may frustrate users and lead to churn.
- **Competition:** Customers may switch to competitors offering better pricing, features, or benefits.

## 4. Type of ML Problem

This is a classification problem because the target variable is categorical.

The model will predict whether a customer will churn or not churn, which is a binary outcome.

## 5. Success Metric

Recall is an important metric in this problem because the goal is to identify as many customers who are likely to churn as possible.

Missing a customer who is going to churn could result in lost revenue, so it is more important to capture most churners, even if some non-churners are incorrectly predicted.

## 6. Risks and Limitations

- **Missing Data:** Incomplete data may lead to incorrect analysis or unreliable model predictions if not handled properly.
- **Limited Sample Size:** If the dataset is too small or not representative, conclusions may not generalise to all customers.
- **Bias in Data:** The data may not represent all types of customers equally, which could lead to biased predictions.
- **Incorrect Assumptions:** Relationships observed in the data may not reflect true causes of churn, leading to misleading conclusions.
- **Real-World Applicability:** Even if the model performs well, it may not work as effectively in real-world scenarios due to changing customer behaviour.
