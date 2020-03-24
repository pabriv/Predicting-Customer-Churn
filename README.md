# Predict Customer Churn to Defend Revenue Streams

---


## Agenda
- [Key Objective](#Key-Objective)
- [Executive Summary](#Executive-Summary)
- [Model Overview & Evaluation](#Model-Overview-&-Evaluation)
- [Integrated Recommendations & Next Steps](#Integrated-Findings)

---

## Key objective

<B>Context:</B><br>
- Businesses that rely on subscription-based revenue models can be greatly impacted by customer churn
- In order to defend topline revenue, businesses should seek to identify customers with high churn risk and escalate them to Customer Success/Outreach teams to mitigate churn and emphasize value prop realization
- Churn data typically highly confidential therefore telco churn data obtained from Kaggle and includes:
    - Demographics (age, gender)
    - Services (e.g. Internet, TV, Phone)
    - Total and Monthly Payments



<B>Key Objectives:</B>
- Improve Churn
- Defend key revenue streams by establishing a Customer Churn Prediction program by applying Machine Learning to customer data
- Prototype Classification System for ongoing identification of customer risk of churn
- Calculate potential salvageable revenue


---


## Executive Summary

- Key objectives: Improve Churn and defend key revenue streams by establishing a Customer Churn Prediction program by applying Machine Learning to Customer Data.  Prototype Classification System for ongoing identification of customer risk of churn and estimate potential salvageable revenue

- Most churned customers were on monthly contracts and canceled within first month likely due to trials. Poor product market fit for Fiber Optic Internet Service likely influenced churn, supported by high correlation, high concentration, and coefficient results

- Myriad Machine Learning Algorithms were applied.  Ultimately Logistic Regression and Neural Network exhibited the highest performance and were then optimized for recall/sensitivity (testing positive for Churn)

- Fiber Optic Internet, Paperless Billing, Elec Check Payments, Senior Citizen status suggest higher likelihood to churn

- In contrast, having a contract, age of customer, higher spend, being subbed to more features (OnlineSecurity, TechSupport Prioritization) suggest higher likelihood to remain subscribed

- Approximately $803K in ARR are conservatively estimated to be recoverable with the Customer Churn Prediction program.  Results will vary depending on product market fit, industry, customer outreach team ability to execute

- Recommendations: trial and refine program. Prioritize customer outreach to predicted churn customers with 0.35 to 0.75 probability, emphasize value proposition and warm transition to customer support if issues exist.  At renewal time consider promotional incentives to boost customer retention


---



## Model Overview & Evaluation


<img src=https://i.imgur.com/B4PFDvL.jpg>


---


<img src=https://i.imgur.com/wG8Yl8B.jpg>



---


## Integrated Recommendations & Next Steps

- Prioritize customer outreach to predicted churn customers with 0.35 to 0.75 probability, emphasize value proposition and warm transition to customer support if issues exist.  At renewal time consider promotional incentives to boost customer retention

- Evaluate fail fast mentality: customers with 75% or higher probability of churn are unlikely to remain, are there any profitability gains by letting them out early and saving on forbiddingly high cloud (e.g. AWS, Azure, Google Cloud) costs, in addition to defending NPS scores

- Additional data: NPS, Product Usage, and Support Case volume (well-known pre-cursors to churn) will drastically increase accuracy of model

- Date/time data and corresponding product releases are critical for SaaS businesses since continuous development and continuous integration will incrementally improve product.  Evaluating churn with a substantially improved product will have different results

- Field customer exit surveys to evaluate leading causes of churn and feed back into product roadmap.  Based on this analysis the data suggests poor product market fit for fiber optic internet service (potentially high price, slow speeds, poor reliability)

- Expand to include Customer Lifetime Value analysis leveraging frequency and recency transactional data

---
